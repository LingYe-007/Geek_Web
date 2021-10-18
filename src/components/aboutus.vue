<template>
  <div id="bs">
    <div class="aboutUs-logo">
      <img
        id="background"
        src="https://photomumu.oss-cn-beijing.aliyuncs.com/%E6%8B%9B%E6%96%B0%E7%BD%91%E7%AB%99%E8%B5%84%E6%96%99/%E8%83%8C%E6%99%AF.png"
      />
      <a href=""
        ><img
          id="leftTop"
          src="https://photomumu.oss-cn-beijing.aliyuncs.com/%E6%8B%9B%E6%96%B0%E7%BD%91%E7%AB%99%E8%B5%84%E6%96%99/1.png"
      /></a>
      <a href="">
        <img
          id="leftBottom"
          src="https://photomumu.oss-cn-beijing.aliyuncs.com/%E6%8B%9B%E6%96%B0%E7%BD%91%E7%AB%99%E8%B5%84%E6%96%99/2.png"
      /></a>
      <a href="">
        <img
          id="center"
          src="https://photomumu.oss-cn-beijing.aliyuncs.com/%E6%8B%9B%E6%96%B0%E7%BD%91%E7%AB%99%E8%B5%84%E6%96%99/3.png"
      /></a>
      <a href="">
        <img
          id="rightTop"
          src="https://photomumu.oss-cn-beijing.aliyuncs.com/%E6%8B%9B%E6%96%B0%E7%BD%91%E7%AB%99%E8%B5%84%E6%96%99/4.png"
      /></a>
      <a href="">
        <img
          id="rightBottom"
          src="https://photomumu.oss-cn-beijing.aliyuncs.com/%E6%8B%9B%E6%96%B0%E7%BD%91%E7%AB%99%E8%B5%84%E6%96%99/5.png"
      /></a>
    </div>
      
  </div>
  

</template>

<style scoped>

@media (min-width: 501px) {
  /*新代码*/

  #bs {
    position: relative;
    left: 0%;
    top: 195vw;
  }
  a img:hover {
    transform: scale(1.5);
  }
  #background {
    position: relative;
    left: 5%;
    width: 85vw;
  }
  #rightTop {
    position: absolute;
    top: 34.8%;
    left: 59%;
    width: 11.8vw;
    transition: all 0.4s;
  }
  #leftTop {
    position: absolute;
    top: 32.4%;
    left: 32.4%;
    width: 11.8vw;
    transition: all 0.4s;
  }
  #leftBottom {
    position: absolute;
    top: 53%;
    left: 23.7%;
    width: 13.5vw;
    transition: all 0.4s;
  }
  #center {
    position: absolute;
    top: 52.3%;
    left: 46.8%;
    width: 9.5vw;
    transition: all 0.4s;
  }
  #rightBottom {
    position: absolute;
    top: 54.2%;
    left: 65.8%;
    width: 13.2vw;
    transition: all 0.4s;
  }

  #about {
    position: absolute;
    top: -40%;
    width: 20vw;
    left: 43%;
  }
}
</style>

