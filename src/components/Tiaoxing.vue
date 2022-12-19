<template>
    <div class="TX">
        <div id="tiao" style=" width: 38vw;height: 40vh;margin-top: 18vh;"></div>
    </div>

</template>
<script >
export default {
    name: 'TX',
    data() {
        return {
            myChart: null,
            option: {
                tooltip: {
                    trigger: 'axis'
                },

                calculable: true,
                xAxis: [
                    {
                        type: 'category',
                        data: ['21年10月', '21年11月', '21年12月', '22年1月',
                            '22年2月', '22年3月', '22年4月', '22年5月',
                            '22年6月', '22年7月', '22年8月', '22年9月',],
                        name: "时间",
                        axisTick: {
                            show: false
                        },
                        axisLabel: {
                            rotate: 25
                        },
                    }
                ],
                yAxis: [
                    {
                        type: 'value',
                        splitLine: false,
                        name: "数量",
                        max: 800000,
                        interval: 100000,
                        axisLine: {
                            show: false
                        },
                        axisTick: {
                            show: false
                        }
                    }
                ],
                series: [
                    {
                        name: 'Rainfall',
                        type: 'bar',
                        barWidth: '20%',
                        data: [
                            40000, 210000, 250000, 300000, 100000, 50000, 35000, 40000, 30000, 60000, 50000, 30000, 20000
                        ],
                        itemStyle: {
                            normal: {
                                color: '#1fdeaf',
                                barBorderRadius: [4, 4, 0, 0]
                            }
                        }
                    }
                    , {
                        name: 'Evaporation',
                        type: 'bar',
                        barWidth: '20%',
                        data: [
                            80000, 300000, 600000, 610000, 620000, 630000, 670000, 650000, 750000, 760000, 770000, 780000
                        ],
                        itemStyle: {
                            normal: {
                                color: '#41b8f9',
                                barBorderRadius: [4, 4, 0, 0]
                            }
                        },

                    }
                ]
            }
        }
    },
    mounted() {
        this.drawEcharts();
    },
    methods: {
        drawEcharts() {
            // 第三步，通过echarts的init方法实例化一个echarts对象myChart，并，保存在data变量中
            this.myChart = this.$echarts.init(document.getElementById("tiao"));
            // 第四步，执行myChart的setOption方法去画图，当然至于配置项，我们要提前配置好，这里的配置项
            //         写在data中，方便我们在一些事件中去修改对应配置项，比如点击按钮更改配置项数据
            this.myChart.setOption(this.option);
            // 第五步，在页面初始化加载的时候绑定页面resize事件监听。补充resize事件：resize事件是在浏览器窗口大小改变时，会触发。
            //        如当用户调整窗口大小，或者最大化、最小化、恢复窗口大小显示时触发 resize 事件。
            //        我们一般使用这个事件去做窗口大小与对应元素的大小适配
            window.addEventListener("resize", () => {
                // 第六步，执行echarts自带的resize方法，即可做到让echarts图表自适应
                this.myChart.resize();
            });
        },
        beforeDestroy() {

            window.removeEventListener("resize", () => {
                this.myChart.resize();
            });
        },
    },
}

</script>
<style>

</style>