<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Document</title>
    <style>
      .stage {
        margin-top: 300px;
        perspective: 500px;
      }
      .cube {
        width: 200px;
        height: 200px;
        margin: 100px auto;
        position: relative;
        transform-style: preserve-3d;
        transform: rotateY(-30deg) rotateX(30deg);
        animation: xixixi 8s linear 0s infinite ;
      }
      .cube:hover .big{
        width: 400px;
        height: 400px;
        opacity: 0.8;
      }
      .side {
        width: 200px;
        height: 200px;
        position: absolute;
        transition: all 0.5s;
      }
      .big{
        width: 200px;
        height: 200px;
        position: absolute;
        opacity: 0;
      }
      .side-top {
        background: rgba(20, 41, 233, 0.5);
        transform: rotateX(-90deg) translateZ(-100px);
      }
      .side-bottom {
        background: rgba(16, 204, 41, 0.5);
        transform: rotateX(90deg) translateZ(-100px);
      }
      .side-left {
        background: rgba(204, 16, 72, 0.5);
        transform: rotateY(90deg) translateZ(-100px);
      }
      .side-right {
        background: rgba(204, 170, 16, 0.5);
        transform: rotateY(-90deg) translateZ(-100px);
      }
      .side-front {
        background: rgba(12, 142, 146, 0.5);
        transform: translateZ(-100px);
      }
      .side-back {
        background: rgba(97, 12, 146, 0.5);
        transform: rotateY(180deg) translateZ(-100px);
      }
      .cube:hover .top {
        background: rgb(20, 41, 233);
        transform: rotateX(-90deg) translateZ(-400px) translateX(-100px);
      }
      .cube:hover .bottom {
        background: rgb(16, 204, 41);
        transform: rotateX(90deg) translateZ(-200px) translateX(-100px);
      }
      .cube:hover .left {
        background: rgb(204, 16, 72);
        transform: rotateY(90deg) translateZ(-400px) translateY(-100px);
      }
      .cube:hover .right {
        background: rgb(204, 170, 16);
        transform: rotateY(-90deg) translateZ(-200px) translateY(-100px);
      }
      .cube:hover .front {
        background: rgb(12, 142, 146);
        transform: rotateY(180deg) translateZ(250px) translateY(-100px) translateX( 100px);
      }
      .cube:hover .back {
        background: rgb(97, 12, 146);
        transform: rotateY(180deg) translateZ(-250px) translateY(-100px)translateX( 100px);
      }
      img {
        width: 100%;
        height: 100%;
      }

      @keyframes xixixi {
        from{
          transform: rotateX(0) rotateY(0);
        }
        to{
          transform: rotateX(360deg) rotateY(360deg);
        }
      }
      /* @keyframes xixixi {
        from{
          transform: rotateY(0);
        }
        to{
          transform: rotateY(360deg) ;
        }
      } */
    </style>
  </head>
  <body>
    <div class="stage">
      <div class="cube">
        <div class="side side-top"><img src="./images/红莲公主.jpg" alt=""></div>
        <div class="side side-bottom"><img src="./images/焰灵姬.jpg" alt=""></div>
        <div class="side side-left"><img src="./images/星魂.jpg" alt=""></div>
        <div class="side side-right"><img src="./images/少羽.jpg" alt=""></div>
        <div class="side side-front"><img src="./images/卫庄.jpg" alt=""></div>
        <div class="side side-back"><img src="./images/焰灵姬 (2).jpg" alt=""></div>
        <div class="side big top"><img src="./images/星魂 (2).jpg" alt=""></div>
        <div class="side big bottom"><img src="./images/焰灵姬 (3).jpg" alt=""></div>
        <div class="side big left"><img src="./images/卫庄 (2).jpg" alt=""></div>
        <div class="side big right"><img src="./images/焰灵姬 (4).jpg" alt=""></div>
        <div class="side big front"><img src="./images/焰灵姬 (5).jpg" alt=""></div>
        <div class="side big back"><img src="./images/星魂 (3).jpg" alt=""></div>
      </div>
    </div>
  </body>
</html>
