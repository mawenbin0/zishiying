<template>
  
  <div class="hello">
    <div class="shexiang">
      <img src="../assets/twostyle/色相／饱和度 1@2x.png" width="100%" height="100%">
    </div>
    <div class="tuceng">
      <img src="../assets/onestyle/图层 8 拷贝@2x.png" width="100%" height="30%">
    </div>
    <div class="tiqu">
      <img src="../assets/twostyle/管控数据提取@2x.png" width="13%" height="3.6%">
    </div>
    <div class="newvue">
      <Body></Body>
    </div>
    <div class="juxing">
      <img src="../assets/twostyle/矩形 2 拷贝 8@2x.png" width="50%" height="8%">
    </div>
    <div style="display: flex;z-index:5;margin-left: 41%;;margin-top: 1%;">
      <img src="../assets/twostyle/管控数据提取@2x.png" width="7%" height="2%">
    </div>
    <div class="xingzhuang">
      <img src="../assets/twostyle/形状 2 拷贝 2@2x.png" width="50%" height="8%">
    </div>
    <div style="display: flex;z-index:5;margin-left: 52%;margin-top: 1%;">
      <img src="../assets/twostyle/涉案数据分析@2x.png" width="7%" height="2%">
    </div>
  </div>

</template>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              

<script>
import Body from './Body.vue';
export default {
components:{
  Body,
}
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
}

html,
body {
  height: 100%;
  display: flex;
  flex-direction: column;
}

div {
  width: 100%;
  height: 100%;
  font-weight: bold;
  position: fixed;
}

.shexiang {
  display: flex;
  z-index: 1;
  position: fixed;
}

.tuceng {
  display: flex;
  justify-content:center;
  margin-top: -1.5%;
  z-index: 5;
 
}

.tiqu {
  display: flex;
  justify-content:center;
  margin-top: 1.5%;
  z-index: 5;

}

.newvue {
  display: flex;
  justify-content:center;
  position: relative;
  z-index: 5;
  width: 96%;
  height: 88%;
  margin-top: 3%;
  margin-left: 2%;
}

.juxing {
  z-index: 5;
  display: flex;
}
.xingzhuang {
  display: flex;
  margin-left: 50%;
  z-index: 5;
}

</style>