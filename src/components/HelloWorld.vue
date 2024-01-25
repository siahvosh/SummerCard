<template>
  <v-container>

    <div class="main-card">
      <div class="flip-card">
        <v-card class="front-card">
          <v-row style="margin-top: 55%">
            <v-col cols="12">
              <v-row justify="center">
                <img class="cloud" src="file:///C:/Users/PC/Desktop/image-from-rawpixel-id-12655439-png.png" alt="">

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
              <img class="cloud-pic" src="file:///C:/Users/PC/Desktop/Untitled-Design.png" alt="">

            </v-col>
          </v-row>
        </v-card>
        <v-card class="back-card">
          <v-row style="margin-top: -60px">

            <v-col cols="12">
              <img class="sea-pic" src="https://assets.codepen.io/1462889/sea.png" alt="">
              <img class="img-1" src="https://assets.codepen.io/1462889/kayak.png" alt="">
              <img class="water-pic" src="https://assets.codepen.io/1462889/water.png" alt="">
            </v-col>
            <v-col cols="12">
              <v-row justify="center">
                <span

                  style="
                    margin-top: 30px;
                    color: #4f4545;
                    font-size: 45px;
                    font-weight: 600;
                    text-transform: uppercase;
                    transform-style: preserve-3d;
                    letter-spacing: 10px;
                    text-shadow: 3px 3px 8px gray;
                    z-index: -1;
                  "
                >kayaking</span>
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
  /*border: 1px solid gray;*/
  margin: 200px auto;
  background: transparent;
  perspective: 1000px;
  cursor: pointer;

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
}

.front-card{
  background: #f1e6d5 !important;
  color: white;
  border: 1px solid red;

  /*overflow: hidden !important;*/
}

.back-card{
  background: #f1ebe0 !important;
  color: white;
  transform: rotateY(180deg);
  /*border: 1px solid gray;*/


}


.img-1{
  transform: translate3d(-50%, 0, 0) perspective(100px);
  filter: opacity(0);
  transform-style: preserve-3d;
  transition: all 0.7s ease 0.3s;
  position: absolute;

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

.water-pic{
  width: 180px;
  z-index: -1;
  transform: translate(200px, 20px);
  filter: opacity(0);
  transition: all 0.4s ease 0.7s;
}

.main-card:hover .water-pic{
  transform: translate(215px, 10px);
  filter: opacity(100%);

}

.main-card:hover .img-1{
  visibility: visible;
  filter: opacity(100%);
  transform: translate3d(-35%, -10%, 30px) perspective(500px);
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
  margin-top: -280px;
  z-index: 0;

}


.cloud-pic{
  width: 100%;
  filter: opacity(100%) drop-shadow(0px 0px 0.8px #000000);
  transform: translate3d(-100px, 24px, 0);
  transition: all 1s ease 0.3s;
  visibility: visible;

}

.flip-card:hover .cloud-pic {
  transform: translate(-70px, 24px);
  visibility: hidden;

}

</style>
