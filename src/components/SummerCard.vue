<template>
  <v-container>

    <div class="main-card">
      <div class="flip-card">
        <v-card class="front-card">
          <v-row style="margin-top: 53%">
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
              <img class="beach-pic" src="file:///C:/Users/PC/Desktop/%E2%80%94Pngtree%E2%80%94green%20sea%20beach%20border%20illustration_6064596.png" alt="">
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
                <img class="sand-pic" src="file:///C:/Users/PC/Desktop/%E2%80%94Pngtree%E2%80%94dust%20smoke%20sandstorm%20sand_7273446.png"  alt=""/>
              </v-row>
            </v-col>
          </v-row>
        </v-card>
      </div>
    </div>

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
  margin: 200px auto;
  background: transparent;
  perspective: 1000px;
  cursor: pointer;
  /*border: 1px solid gray;*/
}
.flip-card{
  width: 100%;
  height: 100%;
  transition: transform 0.8s;
  position: absolute;
  transform-style: preserve-3d;
  /*border: 1px solid gray;*/
}
.main-card:hover .flip-card{
  transform: rotateY(180deg);
}

.front-card, .back-card{
  overflow: revert !important;
  position: absolute !important;
  width: 100%;
  height: 100%;
  backface-visibility: hidden;
}
.front-card{
  background: #f1e6d5 !important;
  color: white;
}

.back-card{
  background: #f1ebe0 !important;
  color: white;
  transform: rotateY(180deg);

}
.kayak{
  width: 430px;
  transform: translate3d(-50%, 5%, 0);
  transform-style: preserve-3d;
  transition: all 0.5s ease 0.3s;
  position: absolute;
}
.main-card:hover .kayak{
  transform: translate3d(-30%, -10%, -80px);
}
.water-pic{
  width: 180px;
  transform: translate(180px, 10px) ;
  filter: opacity(0);
  transition: all 0.4s ease 0.4s;
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
.sand-pic{
  filter: opacity(65%);
  object-fit: cover;
  width: 100%;
  z-index: -1;
  position: absolute;
  top: 25%
}

.beach-pic{
  position: absolute;
  object-fit: cover;
  object-position: bottom;
  width: 100%;
  height: 250px;
  transition: all 1s ease 0.5s;
}

.women-pic{
  position: absolute;
  width: 100%;
  filter: drop-shadow(0px 0px 0.8px #000000);
  transform: translate3d(-100px, 24px, 0);
  transition: all 1s ease 0.3s;
  visibility: visible;
}
.flip-card:hover .women-pic {
  transform: translate(-70px, 24px);
}

.cloud{
  width: 100%;
  margin-top: -180px;
  z-index: 0;
  transform: translate3d(30px, -25px, 50px);
  transform-style: preserve-3d;
  transition: all 1.5s ease;
  rotate: 180deg;
  scale: 1.2;
}
.flip-card:hover .cloud {
  transform: translate3d(-100px, 100px, 0);
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

</style>
