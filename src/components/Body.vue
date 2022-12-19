
<template>
  <div>
    <div class="chibang">
      <img src="../assets/twostyle/翅膀@2x.png" width="96%" height="88%">
    </div>
    <div class="nannv">
      <img src="../assets/twostyle/标题点@2x.png" width="70%" height="14%"
        style="margin-top: 8vh;margin-left: 5vw;z-index: 5;">
      <img src="../assets/twostyle/男女比例@2x.png" width="15%" height="7%"
        style="margin-top: 9vh;margin-left: -16vw;z-index: 10;">
      <div class="yuanhua1">
        <img src="../assets/twostyle/矢量智能对象@2x.png" width="0.8%" height="4%">
        <img src="../assets/twostyle/矢量智能对象@2x.png" width="0.8%" height="4%" class="fanzhuan1">
      </div>

      <div class="yuanhua2">
        <img src="../assets/twostyle/矢量智能对象@2x(1).png" width="0.8%" height="4%">
        <img src="../assets/twostyle/矢量智能对象@2x(1).png" width="0.8%" height="4%" class="fanzhuan2">
      </div>
      <div style="display:flex;z-index: 10;">
        <h2 style="color:white;font-size:0.8rem;margin-left: 10.3vw;
          margin-top: 19.7vh;    letter-spacing: -2px;">58</h2>
        <h2 style="color:white;z-index: 50;font-size:0.2rem;
           margin-top: 22vh; ">.79%</h2>
        <h2 style="color:white;margin-top: 12vh;font-size: 0.5rem;margin-left: -2.8vw; ">男</h2>
      </div>
      <div style="display:flex;z-index: 10;">
        <h2 style="color:white;z-index: 10;font-size:0.8rem;margin-left: 20.3vw;
           margin-top: 19.7vh;     letter-spacing: -2px;">41</h2>
        <h2 style="color:white;z-index: 50;font-size:0.2rem;
          margin-top: 22vh;   ">.21%</h2>
        <h2 style="color:white;margin-top: 12vh;font-size: 0.5rem;margin-left: -2.8vw; ">女</h2>
      </div>
      <div style="margin-top: 15vh;margin-left: 8vw;width: 20%;">
        <div class="element1"></div>
        <div class="element2"></div>
      </div>
    </div>

    <div class="zhiye">
      <img src="../assets/twostyle/标题点@2x.png" width="70%" height="14%"
        style="margin-top: 1vh;margin-left: 5vw;z-index: 5;">
      <img src="../assets/twostyle/职业分布@2x.png" width="15%" height="7%"
        style="margin-top: 2vh;margin-left: -16vw;z-index: 10;">
      <div class="g-progress1">
        <h3 class="g-pro1">自由职业者</h3>
        <h3 class="g-pro2">16.40%</h3>
      </div>
      <div class="g-progress2">
        <h3 class="g-pro1"> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;工人</h3>
        <h3 class="g-pro2">15.07%</h3>
      </div>
      <div class="g-progress3">
        <h3 class="g-pro1">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;学生</h3>
        <h3 class="g-pro2">10.24%</h3>
      </div>
      <div class="g-progress4">
        <h3 class="g-pro1">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;农民</h3>
        <h3 class="g-pro2">9.00%</h3>
      </div>
      <div class="g-progress5">
        <h3 class="g-pro1">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;其他</h3>
        <h3 class="g-pro2">7.56%</h3>
      </div>
      <div class="g-progress6">
        <h3 class="g-pro1">&nbsp; 私人业主</h3>
        <h3 class="g-pro2">5.13%</h3>
      </div>
    </div>


    <div class="zhengzai">
      <img src="../assets/twostyle/标题点@2x.png" width="70%" height="14%" style="margin-left: 5vw;">
      <img src="../assets/twostyle/正在提取中@2x.png" width="16%" height="7%"
        style="margin-left: 9vw; margin-top: -3.6vh;display: flex;">
      <div>
        <table class="table1">
          <tr>
            <th>客户编号</th>
            <th>性别</th>
            <th>客户年龄</th>
            <th>描述</th>
          </tr>
          <tr style="background-color: #163850 !important;">
            <td>1512003******64</td>
            <td>男</td>
            <td>18岁</td>
            <td>工人</td>
          </tr>
          <tr>
            <td>1512003******55</td>
            <td>男</td>
            <td>29岁</td>
            <td>商业贸易行业职员</td>
          </tr>
          <tr style="background-color: #163850 !important;">
            <td>1512003******37</td>
            <td>男</td>
            <td>19</td>
            <td>学生</td>
          </tr>
          <tr>
            <td>1512003******49</td>
            <td>男</td>
            <td>24岁</td>
            <td>社会服务行业职员</td>
          </tr>
        </table>
      </div>
    </div>



    <div class="guankong">
      <img src="../assets/twostyle/标题点@2x.png" width="55%" height="7%" style="margin-top: 13vh;">
      <img src="../assets/twostyle/管控情况@2x.png" width="10%" height="4%" style="margin-top: 13.8vh;margin-left: -17vw;">
        <Tiaoxing></Tiaoxing>
    </div>

    <div class="oneoption">
      <span style="color:white;font-size: 0.45rem;">年龄：</span>
      <span style="color:white;font-size: 0.45rem;font-weight: 200;">{{ age }}</span>&nbsp;
      <img src="../assets/twostyle/右键 拷贝 4@2x.png" width="10%" 
      style="margin-left: 8.5vw;margin-top: -1.5vh;display: flex;">
    </div>

    <div class="twooption">
      <span style="color:white;font-size: 0.45rem;">职业：</span>
      <span style="color:white;font-size: 0.45rem;font-weight: 200;">{{ work }}</span>&nbsp;
      <img src="../assets/twostyle/右键 拷贝 4@2x.png" width="10%" 
      style="margin-left: 8.5vw;margin-top: -1.5vh;display: flex;">
    </div>

    <div class="kstq">
      <img src="../assets/twostyle/组 1@2x.png" width="13%" height="12%">
      <img src="../assets/twostyle/开始提取@2x.png" width="13%" height="12%" style="margin-left: -12.4vw;">
    </div>
    <div style="display: flex; justify-content: center;color:#6994b1;font-size:0.8vw;
       margin-top: 77vh;letter-spacing: -1px;">
      <h3>涉案账户特征包括：年龄段、性别、交易时间、交易频次、</h3>
    </div>
    <div style="display: flex; justify-content: center;color:#6994b1;font-size:0.8vw;
       margin-top: 80.5vh;letter-spacing: -1px;">
      <h3>交易月份，当日最大交易次数等参数综合。</h3>
    </div>

    <div class="kehu">
      <img src="../assets/twostyle/标题点@2x.png" width="70%" height="15.5%"
        style="margin-top: 8vh;margin-left: 1vw;z-index: 5;display: flex;">
      <img src="../assets/twostyle/管控客户数与存量客户数比@2x.png" width="35%" height="8.3%"
        style="margin-top: 8.8vh;margin-left: -16vw;z-index: 10;display: flex;">
      <img src="../assets/twostyle/椭圆 544@2x.png" width="22%"
        style="margin-top: 15vh;margin-left: -7.2vw;z-index: 20;display: flex;">
      <h2 style="color:#80e6ff;z-index: 50;font-size: 0.7rem;margin-left: -4.2vw;margin-top: 19.1vh;">{{ msg }}</h2>
      <h2 style="color:#80e6ff;z-index: 50;font-size: 0.3rem;margin-left: 0.1vw;margin-top: 20.4vh;">%</h2>
    </div>

    <div class="nianlin">
      <img src="../assets/twostyle/标题点@2x.png" width="70%" height="14%"
        style="margin-top: 2vh;margin-left: 1vw;z-index: 5;">
      <img src="../assets/twostyle/年龄分布@2x.png" width="15%" height="7%"
        style="margin-top: 3vh;margin-left: -16vw;z-index: 10;">
      <div class="Echarts">
        <div id="main" style=" width: 21vw;height: 30vh;position: absolute;"></div>
      </div>
    </div>

    <div class="jieguo">
      <img src="../assets/twostyle/标题点@2x.png" width="70%" height="14%"
        style="margin-top: 1vh;margin-left: 1vw;z-index: 5;">
      <img src="../assets/twostyle/提取结果@2x.png" width="15%" height="7%"
        style="margin-top: 2vh;margin-left: -16vw;z-index: 10;">
      <div>
        <table class="table2">
          <tr>
            <th>客户编号</th>
            <th>性别</th>
            <th>客户年龄</th>
            <th>描述</th>
          </tr>
          <tr style="background-color: #15768d !important;">
            <td>1512003******64</td>
            <td>男</td>
            <td>18岁</td>
            <td>工人</td>
          </tr>

          <tr>
            <td>1512003******55</td>
            <td>男</td>
            <td>29岁</td>
            <td>商业贸易行业职员</td>
          </tr>
          <tr style="background-color: #15768d !important;">
            <td>1512003******37</td>
            <td>男</td>
            <td>19</td>
            <td>学生</td>
          </tr>
          <tr>
            <td>1512003******49</td>
            <td>男</td>
            <td>24岁</td>
            <td>社会服务行业职员</td>
          </tr>
        </table>
      </div>
    </div>
  </div>
</template>


<script >
import Tiaoxing from './Tiaoxing.vue';
export default {
  name: 'Echarts',
  data() {
    return {
      msg: 34,
      age: "10岁到70岁",
      work: "学生、农民",
      myChart: null,
      option: {
        xAxis: {
          type: 'category',
          data: ['10', '20', '30', '40', '50', '60', '70']
        },
        yAxis: {
          type: 'value',
          max: 50,
          splitLine: false
        },
        series: [
          {
            data: [10, 30, 40, 35, 20, 18, 8],
            type: 'line',
            itemStyle: {
              normal: {
                color: '#30c1dd'
              }
            },
            areaStyle: {
              normal: {
                color: '#112f43'
              }
            },
          },

        ]
      }
    };
  },
  components: {
    Tiaoxing
  },
  mounted() {
    this.drawEcharts();
  },
  methods: {
    drawEcharts() {
      // 第三步，通过echarts的init方法实例化一个echarts对象myChart，并，保存在data变量中
      this.myChart = this.$echarts.init(document.getElementById("main"));
      // 第四步，执行myChart的setOption方法去画图，当然至于配置项，我们要提前配置好，这里的配置项
      //         写在data中，方便我们在一些事件中去修改对应配置项，比如点击按钮更改配置项数据
      this.myChart.setOption(this.option);
      // 第五步，在页面初始化加载的时候绑定页面resize事件监听。补充resize事件：resize事件是在浏览器窗口大小改变时，会触发。
      //        如当用户调整窗口大小，或者最大化、最小化、恢复窗口大小显示时触发 resize 事件。
      //        我们一般使用这个事件去做窗口大小与对应元素的大小适配
      window.addEventListener("resize", () => {
        // 第六步，执行echarts自带的resize方法，即可做到让echarts图表自适应
        this.myChart.resize();
        // 如果有多个echarts，就在这里执行多个echarts实例的resize方法,不过一般要做组件化开发，即一个.vue文件只会放置一个echarts实例
        /*
        this.myChart2.resize();
        this.myChart3.resize();
        ......
        */
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


<style scoped>
* {
  margin: 0;
  padding: 0;
}


.chibang {
  display: flex;
  justify-content: center;
  z-index: 2;

}

.nannv {
  display: flex;
  margin-left: 2%;
  z-index: 3;
  width: 28%;
  height: 29vh;

}


.zhiye {
  display: flex;
  margin-top: 29vh;
  margin-left: 2%;
  z-index: 6;
  width: 28%;
  height: 29vh;
}



.zhengzai {
  margin-top: 58vh;
  margin-left: 2%;
  z-index: 6;
  width: 31%;
  height: 30vh;
}


.guankong {
  display: flex;
  margin-left: 32vw;
  z-index: 7;
  width: 38vw;
  height: 58vh;
}


.kehu {
  display: flex;
  margin-left: 70vw;
  width: 28%;
  height: 27vh;
  z-index: 3;
}


.nianlin {
  display: flex;
  margin-top: 27vh;
  margin-left: 70vw;
  z-index: 3;
  width: 28%;
  height: 30vh;

}

.Echarts {
  margin-top: 2vh;

}

.jieguo {
  display: flex;
  margin-top: 57vh;
  margin-left: 70vw;
  z-index: 3;
  width: 28%;
  height: 31vh;

}

.kstq {
  margin-top: 64vh;
  display: flex;
  margin-left: 42.5vw;
}


.g-progress1 {
  margin-top: 8vh;
  margin-left: 7.5%;
  width: 14%;
  height: 0.5vh;
  background: linear-gradient(90deg, #ea68a2 16.4%, #0a537f 16.4%);
  z-index: 5;

}

.g-progress2 {
  margin-top: 11.2vh;
  margin-left: 7.5%;
  width: 14%;
  height: 0.5vh;
  background: linear-gradient(90deg, #13aaef 15%, #0a537f 15%);
  z-index: 5;

}

.g-progress3 {
  margin-top: 14.4vh;
  margin-left: 7.5%;
  width: 14%;
  height: 0.5vh;
  background: linear-gradient(90deg, orange 10%, #0a537f 10.24%);
  z-index: 5;

}

.g-progress4 {
  margin-top: 17.6vh;
  margin-left: 7.5%;
  width: 14%;
  height: 0.5vh;
  background: linear-gradient(90deg, #4cdad6 9%, #0a537f 9%);
  z-index: 5;

}

.g-progress5 {
  margin-top: 20.8vh;
  margin-left: 7.5%;
  width: 14%;
  height: 0.5vh;
  background: linear-gradient(90deg, yellow 7%, #0a537f 7.56%);
  z-index: 5;

}

.g-progress6 {
  margin-top: 24vh;
  margin-left: 7.5%;
  width: 14%;
  height: 0.5vh;
  background: linear-gradient(90deg, pink 5%, #0a537f 5.13%);
  z-index: 5;

}



.element1 {
  width: 6vw;
  height: 11vh;
  margin: 0 auto;
  border-radius: 50%;
  border: solid #00a0e9;
  border-width: 0.8vh;
  background: linear-gradient(rgb(0, 1, 1, 0.001) 50%, #0d4a69 50%);
  z-index: 6;
}

.element2 {
  width: 6vw;
  height: 11vh;
  margin: 0 auto;
  border-radius: 50%;
  border: solid #ea68a2;
  border-width: 0.8vh;
  background: linear-gradient(rgb(0, 1, 1, 0.001) 50%, #482e48 50%);
  margin-left: 10vw;
  z-index: 6;
}

.yuanhua1 {
  margin-top: 19vh;
  margin-left: 9.6vw;
  z-index: 10;
}

.yuanhua2 {
  margin-top: 19vh;
  margin-left: 19.6vw;
  z-index: 10;
}

.fanzhuan1 {
  transform: rotateY(180deg);
  margin-left: -1.5vw;

}

.fanzhuan2 {
  transform: rotateY(180deg);
  margin-left: -1.5vw;

}

.g-pro1 {
  color: rgba(255, 255, 255, 0.731);
  margin-top: -1vh;
  margin-left: -5vw;
  font-size: 0.4rem;
}

.g-pro2 {
  color: rgba(255, 255, 255, 0.548);
  position:absolute;
  margin-top: -2vh;
  margin-left: 15vw;
  font-size: 0.4rem;
}

.oneoption {
  margin-top: 58vh;
  margin-left: 38.5vw;
  width: 10%;
  height: 4%;
  border-radius: 20px;
  text-align: center;
  line-height: 2vh;
  border-style: solid;
  border-color: #85faff;
  background-color: #173B56;


}

.twooption {
  margin-top: 58vh;
  margin-left: 50vw;
  width: 10%;
  height: 4%;
  border-radius: 20px;
  text-align: center;
  line-height: 2vh;
  border-style: solid;
  border-color: #85faff;
  background-color: #173B56;
}

th {
  color: #00a0e9 !important;
}

.table1 {
  color: white;
  font-size: 0.4rem;
  margin-top: 1vh;
  margin-left: 7%;
  width: 21vw;
  line-height: 4vh;
  border-collapse: collapse;
}


.table2 {
  color: white;
  margin-top: 6vh;
  margin-left: 1vw;
  font-size: 0.4rem;
  width: 20.5vw;
  line-height: 4vh;
  border-collapse: collapse;
}
</style>
