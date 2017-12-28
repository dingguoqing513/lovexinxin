<template>
  <div class="First-container">
    <img class="heartleftbg" src="~/static/first/redheart.png">
    <img class="heartrightbg" src="~/static/first/redheart.png">
  </div>
</template>

<script>
  
</script>

<style lang="less" scoped>
  .First-container{
    width:100vw;
    height:100vh;
    display: flex;
    position: relative;
    left:0;
    right:0;
    top:0;
    bottom:0;
    .heartleftbg{
      width:30px;
      height:30px;
      display: inline-block;
      background: url('~/static/first/redheart.png') center no-repeat;
      background-size:100%;
      position: absolute;
      animation:first 6s forwards;
      -webkit-animation:first 6s forwards;
    }
    .heartrightbg{
      width:30px;
      height:30px;
      display: inline-block;
      background: url('~/static/first/redheart.png') center no-repeat;
      background-size:100%;
      position: absolute;
      animation:second 6s forwards;
      -webkit-animation:first 6s forwards;
    }
    .headerbox-right{
      display: flex;
      height:30px;
      position: absolute;
      right:0;
      animation:second 6s forwards;
      .heartbg{
        width:30px;
        height:30px;
        display: inline-block;
        background: url('~/static/first/redheart.png') center no-repeat;
        background-size:100%;
      }
    }
    // .inputText{
    //   width:45px;
    //   height:25px;
    //   border-image-source: url('~/static/dog.png');
    //   border-image-width: 50;
    //   border-image-slice: 57 318 124 47 fill;
    // }
  }
  @keyframes first {
    0% {
      left:46%;
      top:2%;
      transform:scale(1);
    }
    20% {
      left:2%;
      top:2%;
      transform:scale(1);
    }
    40% {
      left:2%;
      top:96%;
      transform:scale(1);
    }
    45% {
      top:60%;
      left:46%;
      transform:scale(1);
    }
    60% {
      top:45%;
      left:46%;
      transform:scale(1);
    }
    63% {
      top:43%;
      left:46%;
      transform:scale(5);
      -wekit-transform:scale(5);
    }
    68% {
      top:42%;
      left:46%;
      transform:scale(2);
      -wekit-transform:scale(2);
    }
    71% {
      top:41%;
      left:46%;
      transform:scale(5);
      -wekit-transform:scale(5);
    }
    76% {
      top:40%;
      left:46%;
      transform:scale(2);
      -wekit-transform:scale(2);
    }
    79% {
      top:39%;
      left:46%;
      transform:scale(5);
      -wekit-transform:scale(5);
    }
    84% {
      top:38%;
      left:46%;
      transform:scale(2);
      -wekit-transform:scale(2);
    }
    87% {
      top:37%;
      left:46%;
      transform:scale(5);
      -wekit-transform:scale(5);
    }
    92% {
      top:36%;
      left:46%;
      transform:scale(2);
      -wekit-transform:scale(2);
    }
    95% {
      top:35%;
      left:46%;
      transform:scale(5);
      -wekit-transform:scale(5);
    }
    100% {
      top:34%;
      left:46%;
      transform:scale(1);
      -wekit-transform:scale(1);
    }
  }
  @keyframes second {
    0% {
      right:46%;
      top:2%;
      transform:scale(1);
    }
    20% {
      right:2%;
      top:2%;
      transform:scale(1);
    }
    40% {
      right:2%;
      top:96%;
      transform:scale(1);
    }
    45% {
      top:60%;
      right:46%;
      transform:scale(1);
    }
    60% {
      top:45%;
      right:46%;
      transform:scale(1);
    }
    63% {
      top:43%;
      right:46%;
      transform:scale(5);
      -wekit-transform:scale(5);
    }
    68% {
      top:42%;
      right:46%;
      transform:scale(2);
      -wekit-transform:scale(2);
    }
    71% {
      top:41%;
      right:46%;
      transform:scale(5);
      -wekit-transform:scale(5);
    }
    76% {
      top:40%;
      right:46%;
      transform:scale(2);
      -wekit-transform:scale(2);
    }
    79% {
      top:39%;
      right:46%;
      transform:scale(5);
      -wekit-transform:scale(5);
    }
    84% {
      top:38%;
      right:46%;
      transform:scale(2);
      -wekit-transform:scale(2);
    }
    87% {
      top:37%;
      right:46%;
      transform:scale(5);
      -wekit-transform:scale(5);
    }
    92% {
      top:36%;
      right:46%;
      transform:scale(2);
      -wekit-transform:scale(2);
    }
    95% {
      top:35%;
      right:46%;
      transform:scale(5);
      -wekit-transform:scale(5);
    }
    100% {
      top:34%;
      right:46%;
      transform:scale(1);
      -wekit-transform:scale(1);
    }
  }
  

</style>