<template>
  <v-container>

    <div class="main-card">
      <div class="flip-card">
        <v-card class="front-card">
          <v-row style="margin-top: 55% ;">
            <v-col cols="12">
              <v-row justify="center">
                <img class="cloud" src="file:///C:/Users/PC/Desktop/%E2%80%94Pngtree%E2%80%94white%20cloud%20png%20element%20with_7267714.png" alt="">
                <span
                   style="
                    position: absolute;
                    margin: -40px 0 0 10px ;
                    color: #5a8681;
                    font-size: 50px;
                    font-weight: 600;
                    text-transform: uppercase;
                    transform-style: preserve-3d;
                    letter-spacing: 15px;
                    text-shadow: 3px 3px 8px gray;
                  "
                 >summer</span>
              </v-row>
              <img class="mount-pic" src="file:///C:/Users/PC/Desktop/%E2%80%94Pngtree%E2%80%94green%20sea%20beach%20border%20illustration_6064596.png" alt="">
              <img class="women-pic" src="file:///C:/Users/PC/Desktop/Untitled-Design.png" alt="">
            </v-col>
          </v-row>
        </v-card>

        <v-card class="back-card">
          <v-row style="margin-top: -60px;">
            <v-col cols="12">
              <img class="sea-pic" src="https://assets.codepen.io/1462889/sea.png" alt="">
              <img class="kayak" src="https://assets.codepen.io/1462889/kayak.png" alt="">
              <img class="water-pic" src="https://assets.codepen.io/1462889/water.png" alt="">
            </v-col>
            <v-col cols="12">
              <v-row justify="center" style="transform:  perspective(10000px) !important;   z-index: 2 !important; ">
                <span class="nameCard">kayaking</span>
              </v-row>
            </v-col>
            <v-col cols="12">
              <v-row justify="center">
<!--                 <span style="color: #27dc7b; margin: 20px 0 0 5px; padding: 20px">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusantium, deleniti eius eum laboriosam odit quidem sapiente. Illo nesciunt provident rem? </span>-->
                <img style="filter: opacity(65%); object-fit: cover; width: 100%;z-index: -1; position: absolute; top: 25%" src="file:///C:/Users/PC/Desktop/%E2%80%94Pngtree%E2%80%94dust%20smoke%20sandstorm%20sand_7273446.png"  alt=""/>
              </v-row>
            </v-col>
          </v-row>
        </v-card>
      </div>
    </div>


<!--    -->
<!--    <div class="section over-hide">-->
<!--      <div class="container">-->
<!--        <div class="row full-height justify-content-center">-->
<!--          <div class="col-12 text-center align-self-center py-5">-->
<!--            <div class="section text-center py-5 py-md-0">-->
<!--              <input class="pricing" type="checkbox" id="pricing" name="pricing"/>-->
<!--              <label for="pricing"><span class="block-diff">kayaking<span class="float-right">camping</span></span></label>-->
<!--              <div class="card-3d-wrap mx-auto">-->
<!--                <div class="card-3d-wrapper">-->
<!--                  <div class="card-front">-->
<!--                    <div class="pricing-wrap">-->
<!--                      <h4 class="mb-5">Kayaking</h4>-->
<!--                      <h2 class="mb-2"><sup>$</sup>39 / 4<sup>hrs</sup></h2>-->
<!--                      <p class="mb-4">per person</p>-->
<!--                      <p class="mb-1"><i class="uil uil-location-pin-alt size-22"></i></p>-->
<!--                      <p class="mb-4">Drina, Serbia</p>-->
<!--                      <a href="#0" class="link">Choose Date</a>-->
<!--                      <div class="img-wrap img-2">-->
<!--                        <img src="https://assets.codepen.io/1462889/sea.png" alt="">-->
<!--                      </div>-->
<!--                      <div class="img-wrap img-1">-->
<!--                        <img src="https://assets.codepen.io/1462889/kayak.png" alt="">-->
<!--                      </div>-->
<!--                      <div class="img-wrap img-3">-->
<!--                        <img src="https://assets.codepen.io/1462889/water.png" alt="">-->
<!--                      </div>-->
<!--                      <div class="img-wrap img-6">-->
<!--                        <img src="https://assets.codepen.io/1462889/Stone.png" alt="">-->
<!--                      </div>-->
<!--                    </div>-->
<!--                  </div>-->
<!--                  <div class="card-back">-->
<!--                    <div class="pricing-wrap">-->
<!--                      <h4 class="mb-5">Camping</h4>-->
<!--                      <h2 class="mb-2"><sup>$</sup>29 / 8<sup>hrs</sup></h2>-->
<!--                      <p class="mb-4">per person</p>-->
<!--                      <p class="mb-1"><i class="uil uil-location-pin-alt size-22"></i></p>-->
<!--                      <p class="mb-4">Tara, Serbia</p>-->
<!--                      <a href="#0" class="link">Choose Date</a>-->
<!--                      <div class="img-wrap img-2">-->
<!--                        <img src="https://assets.codepen.io/1462889/grass.png" alt="">-->
<!--                      </div>-->
<!--                      <div class="img-wrap img-4">-->
<!--                        <img src="https://assets.codepen.io/1462889/camp.png" alt="">-->
<!--                      </div>-->
<!--                      <div class="img-wrap img-5">-->
<!--                        <img src="https://assets.codepen.io/1462889/Ivy.png" alt="">-->
<!--                      </div>-->
<!--                      <div class="img-wrap img-7">-->
<!--                        <img src="https://assets.codepen.io/1462889/IvyRock.png" alt="">-->
<!--                      </div>-->
<!--                    </div>-->
<!--                  </div>-->
<!--                </div>-->
<!--              </div>-->
<!--            </div>-->
<!--          </div>-->
<!--        </div>-->
<!--      </div>-->
<!--    </div>-->
  </v-container>
</template>

<script >

  export default {


  };

</script>


<style >
@import url('https://fonts.cdnfonts.com/css/fantasy');
*{
  font-family: 'Fantasy', sans-serif ;
}

.main-card{
  width: 300px;
  height: 400px;
  /*border: 1px solid gray;*/
  margin: 200px auto;
  background: transparent;
  perspective: 1000px;
  cursor: pointer;
  transform-style: preserve-3d;
}
.flip-card{
  width: 100%;
  height: 100%;
  position: relative !important;
  transition: transform 1s;
  transform-style: preserve-3d;
}
.main-card:hover .flip-card{
  transform: rotateY(180deg);
}

.front-card, .back-card{
  overflow: revert !important;
  position: absolute !important;
  width: 100%;
  height: 100%;
  backface-visibility: hidden ;
  transform-style: preserve-3d;
}
.front-card{
  background: #f1e6d5 !important;
  color: white;
}
.back-card{
  perspective: 1000px;
  background: #f1ebe0 !important;
  color: white;
  transform: rotateY(180deg);
  z-index: 1;
}

.kayak{
  width: 430px;
  transform: translate3d(-50%, 5%, 0) perspective(1000px);
  filter: opacity(0);
  transform-style: preserve-3d;
  transition: all 0.5s ease  0.4s;
  position: absolute;
}
.main-card:hover .kayak{
  visibility: visible;
  filter: opacity(100%);
  transform: translate3d(-30%, -10%, -80px) perspective(500px) ;
}

.water-pic{
  width: 180px;
  z-index: -1;
  transform: translate(180px, 10px) ;
  filter: opacity(0);
  transition: all 0.4s ease 0.5s;
}
.main-card:hover .water-pic{
  transform: translate(205px, 3px);
  filter: opacity(100%);
}

.sea-pic{
  position: absolute;
  object-position: center;
  object-fit: cover;
  overflow: revert;
  margin-top: 50px;
  width: 100%;
  height: 200px;
}


.mount-pic{
  position: absolute;
  object-fit: cover;
  object-position: bottom;
  width: 100%;
  height: 250px;
  /*transform: translate(90px, 1px);*/
  transition: all 1s ease 0.5s;
}

.cloud{
  width: 100%;
  margin-top: -180px;
  z-index: 0;
  transform: translate3d(30px, -30px, 50px);
  transform-style: preserve-3d;
  transition: all 1.5s ease;
  rotate: 180deg;
  scale: 1.2;
}
.flip-card:hover .cloud {
  transform: translate3d(-100px, 100px, 0);
  visibility: hidden;
}


.women-pic{
  width: 100%;
  filter: opacity(100%) drop-shadow(0px 0px 0.8px #000000);
  transform: translate3d(-100px, 24px, 0);
  transition: all 1s ease 0.3s;

  visibility: visible;
}
.flip-card:hover .women-pic {
  transform: translate(-70px, 24px);
  visibility: hidden;
}

.nameCard{
  margin: 30px 25px 0 23px ;
  color: #314e53;
  font-size: 45px;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 10px;
  position: absolute;
  text-shadow: 3px 3px 8px gray;
  transform-style: preserve-3d !important;
  transform: translate3d(0, 10px, 50px)  perspective(1000px);
}
.nameCard:before{
  position: absolute;
  content: '';
  z-index: -1;
  background: linear-gradient(217deg, #448ad5, #b8eaf9);
  width: 70px;
  height: 70px;
  display: block;
  top: 50%;
  left: 50%;
  transform: translate(-60%, -60%);
  box-shadow: 0 6px 20px 0 rgba(16, 39, 112,.3);
  animation: border-transform 5s linear infinite;
}
@keyframes border-transform{
  0%,100% { border-radius: 63% 37% 54% 46% / 55% 48% 52% 45%; }
  14% { border-radius: 40% 60% 54% 46% / 49% 60% 40% 51%; }
  28% { border-radius: 54% 46% 38% 62% / 49% 70% 30% 51%; }
  42% { border-radius: 61% 39% 55% 45% / 61% 38% 62% 39%; }
  56% { border-radius: 61% 39% 67% 33% / 70% 50% 50% 30%; }
  70% { border-radius: 50% 50% 34% 66% / 56% 68% 32% 44%; }
  84% { border-radius: 46% 54% 50% 50% / 35% 61% 39% 65%; }
}









/*@import url('https://fonts.googleapis.com/css?family=Poppins:400,500,600,700,800,900');*/

:root{
  font-size: 20px;
}
body{
  font-family: 'Poppins', sans-serif;
  font-weight: 500;
  font-size: 15px;
  line-height: 1.7;
  color: #102770;
  background-color: #180148;
  overflow-x: hidden;
}
a {
  cursor: pointer;
  transition: all 200ms linear;
}
a:hover {
  text-decoration: none;
}
.link {
  color: #c4c3ca;
}
.link:hover {
  color: #ffeba7;
}
.over-hide {
  overflow: hidden;
}
.size-22{
  font-size: 22px;
}
.section{
  position: relative;
  width: 100%;
  z-index: 1;
  display: block;
}
.full-height{
  min-height: 100vh;
}
[type="checkbox"]:checked,
[type="checkbox"]:not(:checked){
  position: absolute;
  left: -9999px;
}
.pricing:checked + label,
.pricing:not(:checked) + label{
  position: relative;
  display: block;
  text-align: center;
  width: 260px;
  height: 44px;
  border-radius: 4px;
  padding: 0;
  margin: 0 auto;
  cursor: pointer;
  font-family: 'Poppins', sans-serif;
  font-weight: 600;
  text-transform: uppercase;
  font-size: 14px;
  letter-spacing: 1px;
  line-height: 44px;
  padding: 0 25px;
  padding-right: 27px;
  overflow: hidden;
  color: #fff;
  text-align: left;
}
.pricing:checked + label:before,
.pricing:not(:checked) + label:before{
  position: absolute;
  content: '';
  z-index: -2;
  background-color: #102770;
  width: 100%;
  height: 100%;
  display: block;
  top: 0;
  left: 0;
}
.pricing:checked + label:after,
.pricing:not(:checked) + label:after{
  position: absolute;
  content: '';
  z-index: -1;
  background-color: #ffeba7;
  width: 128px;
  height: 40px;
  display: block;
  top: 2px;
  left: 2px;
  border-radius: 2px;
  transition: left 300ms linear;
}
.pricing:checked + label:after {
  left: 130px;
}
.block-diff {
  display: block;
  mix-blend-mode: difference;
}

.card-3d-wrap {
  position: relative;
  width: 340px;
  max-width: calc(100% - 20px);
  height: 510px;
  -webkit-transform-style: preserve-3d;
  transform-style: preserve-3d;

  margin-top: 90px;
}
.card-3d-wrapper {
  width: 100%;
  height: 100%;
  position:absolute;
  top: 0;
  left: 0;
  -webkit-transform-style: preserve-3d;
  transform-style: preserve-3d;
  transition: transform 700ms 400ms ease-out;
}
.card-front, .card-back {
  width: 100%;
  height: 100%;
  background-color: rgba(255, 255, 255, 1);
  position: absolute;
  border-radius: 6px;
  left: 0;
  top: 0;
  -webkit-transform-style: preserve-3d;
  transform-style: preserve-3d;
  -webkit-backface-visibility: hidden;
  -moz-backface-visibility: hidden;
  -o-backface-visibility: hidden;
  backface-visibility: hidden;
  box-shadow: 0 12px 35px 0 rgba(16, 39, 112,.07);
}
.card-back {
  transform: rotateY(180deg);
}
.pricing:checked ~ .card-3d-wrap .card-3d-wrapper {
  transform: rotateY(180deg);
  transition: transform 700ms 400ms ease-out;
}
.pricing-wrap{
  position: relative;
  padding-top: 160px;
  width: 100%;
  display: block;
  z-index: 1;
  -webkit-transform-style: preserve-3d;
  transform-style: preserve-3d;
  -webkit-backface-visibility: hidden;
  -moz-backface-visibility: hidden;
  -o-backface-visibility: hidden;
  backface-visibility: hidden;
}
.pricing-wrap h4{
  position: relative;
  width: 100%;
  display: block;
  text-align: center;
  font-family: 'Poppins', sans-serif;
  font-weight: 700;
  letter-spacing: 3px;
  font-size: 22px;
  line-height: 1.7;
  color: #102770;
  transform: translate3d(0, 0, 35px) perspective(100px);
}
.pricing-wrap h4:before{
  position: absolute;
  content: '';
  z-index: -1;
  background: linear-gradient(217deg, #448ad5, #b8eaf9);
  width: 70px;
  height: 70px;
  display: block;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  box-shadow: 0 6px 20px 0 rgba(16, 39, 112,.3);
  animation: border-transform 6s linear infinite;
}
.card-back .pricing-wrap h4:before{
  background: linear-gradient(217deg, #648946, #a3c984);
}
@keyframes border-transform{
  0%,100% { border-radius: 63% 37% 54% 46% / 55% 48% 52% 45%; }
  14% { border-radius: 40% 60% 54% 46% / 49% 60% 40% 51%; }
  28% { border-radius: 54% 46% 38% 62% / 49% 70% 30% 51%; }
  42% { border-radius: 61% 39% 55% 45% / 61% 38% 62% 39%; }
  56% { border-radius: 61% 39% 67% 33% / 70% 50% 50% 30%; }
  70% { border-radius: 50% 50% 34% 66% / 56% 68% 32% 44%; }
  84% { border-radius: 46% 54% 50% 50% / 35% 61% 39% 65%; }
}
.pricing-wrap h2{
  position: relative;
  width: 100%;
  display: block;
  text-align: center;
  font-family: 'Poppins', sans-serif;
  font-weight: 400;
  letter-spacing: 1px;
  font-size: 36px;
  line-height: 1.1;
  color: #102770;
  transform: translate3d(0, 0, 30px) perspective(100px);
}
.pricing-wrap h2 sup{
  font-size: 20px;
}
.pricing-wrap p{
  position: relative;
  width: 100%;
  display: block;
  text-align: center;
  font-family: 'Poppins', sans-serif;
  font-weight: 500;
  font-size: 14px;
  line-height: 1.2;
  letter-spacing: 1px;
  color: #102770;
  transform: translate3d(0, 0, 30px) perspective(100px);
}
.card-back h2,
.card-back p,
.card-back h4{
  color: #0c1c00;
}
.link {
  position: relative;
  padding: 10px 20px;
  border-radius: 4px;
  display: inline-block;
  text-align: center;
  color: #ffeba7;
  background-color: #102770;
  transition: all 200ms linear;
  font-family: 'Poppins', sans-serif;
  font-weight: 500;
  font-size: 14px;
  line-height: 1.2;
  transform: translate3d(0, 0, 30px) perspective(100px);
}
.link:hover {
  color: #102770;
  background-color: #ffeba7;
}
.card-back .link{
  background-color: #0c1c00;
}
.card-back .link:hover{
  color: #0c1c00;
  background-color: #ffeba7;
}
.img-wrap img{
  width: 100%;
  height: auto;
  display: block;
}
.img-1{
  position: absolute;
  display: block;
  left: -160px;
  top: -50px;
  z-index: 5;
  width: calc(80% + 160px);
  transform: translate3d(0, 0, 45px) perspective(100px);
  opacity: 1;
  pointer-events: auto;
  transition: transform 400ms 1200ms ease, opacity 400ms 1200ms ease;
}
.pricing:checked ~ .card-3d-wrap .card-3d-wrapper .img-1 {
  opacity: 0;
  transform: translate3d(-50px, 25px, 45px) perspective(100px);
  pointer-events: none;
  transition: transform 400ms ease, opacity 200ms 150ms ease;
}
.img-2 {
  position: absolute;
  display: block;
  left: 0;
  top: 0;
  z-index: 1;
  border-top-left-radius: 6px;
  border-top-right-radius: 6px;
  overflow: hidden;
  width: 100%;
  transform: translate3d(0, 0, 15px) perspective(100px);
}
.img-3{
  position: absolute;
  display: block;
  right: -20px;
  top: -40px;
  z-index: 5;
  width: calc(60% + 20px);
  transform: translate3d(0, 0, 55px) perspective(100px) scale(1);
  opacity: 1;
  pointer-events: auto;
  transition: transform 300ms 1300ms ease, opacity 200ms 1300ms ease;
}
.pricing:checked ~ .card-3d-wrap .card-3d-wrapper .img-3 {
  opacity: 0;
  transform: translate3d(-50px, 5px, 55px) perspective(100px) scale(0.4);
  pointer-events: none;
  transition: transform 400ms ease, opacity 200ms 150ms ease;
}
.img-6{
  position: absolute;
  display: block;
  right: -20px;
  bottom: -55px;
  z-index: 5;
  width: calc(20% + 30px);
  transform: translate3d(0, 0, 25px) perspective(100px) scale(1);
  opacity: 1;
  pointer-events: auto;
  transition: transform 300ms 1300ms ease, opacity 200ms 1300ms ease;
}
.pricing:checked ~ .card-3d-wrap .card-3d-wrapper .img-6 {
  opacity: 0;
  transform: translate3d(0, 0, 25px) perspective(100px) scale(0.4);
  pointer-events: none;
  transition: transform 400ms ease, opacity 200ms 150ms ease;
}

.img-4{
  position: absolute;
  display: block;
  left: -60px;
  top: -60px;
  z-index: 5;
  width: calc(65% + 60px);
  transform: translate3d(0, 0, 45px) perspective(100px) scale(0.5);
  opacity: 0;
  pointer-events: none;
  transition: transform 400ms ease, opacity 200ms 150ms ease;
}
.pricing:checked ~ .card-3d-wrap .card-3d-wrapper .img-4 {
  opacity: 1;
  pointer-events: auto;
  transform: translate3d(0, 0, 45px) perspective(100px) scale(1);
  transition: transform 400ms 1200ms ease, opacity 300ms 1200ms ease;
}
.img-5{
  position: absolute;
  display: block;
  right: -70px;
  top: -50px;
  z-index: 6;
  width: calc(60% + 70px);
  transform: translate3d(0, 0, 35px) perspective(100px) scale(0.5) rotate(0deg);
  opacity: 0;
  pointer-events: none;
  transition: transform 400ms 100ms ease, opacity 200ms 250ms ease;
}
.pricing:checked ~ .card-3d-wrap .card-3d-wrapper .img-5 {
  opacity: 1;
  pointer-events: auto;
  transform: translate3d(0, 0, 35px) perspective(100px) scale(1) rotate(10deg);
  transition: transform 400ms 1300ms ease, opacity 300ms 1300ms ease;
}
.img-7{
  position: absolute;
  display: block;
  right: -30px;
  bottom: -65px;
  z-index: 6;
  width: calc(25% + 30px);
  transform: translate3d(0, 0, 35px) perspective(100px) scale(0.5);
  opacity: 0;
  pointer-events: none;
  transition: transform 400ms 100ms ease, opacity 200ms 250ms ease;
}
.pricing:checked ~ .card-3d-wrap .card-3d-wrapper .img-7 {
  opacity: 1;
  pointer-events: auto;
  transform: translate3d(0, 0, 35px) perspective(100px) scale(1);
  transition: transform 400ms 1300ms ease, opacity 300ms 1300ms ease;
}



.logo {
  position: fixed;
  top: 30px;
  right: 30px;
  display: block;
  z-index: 100;
  transition: all 250ms linear;
}
.logo img {
  height: 26px;
  width: auto;
  display: block;
}








</style>
