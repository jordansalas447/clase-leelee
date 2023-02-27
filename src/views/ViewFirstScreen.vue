<template>
  <div>
    <div v-if="change">
      <div class="ViewFirstScreen text-white">
        <div class="background-color text-center">
          <div class="row py-5">
            <div class="col-lg-5 my-auto">
              <div class="text-dark rounded">
                <div class="">
                  <div data-aos="zoom-in" data-aos-delay="200" style="font-size: 50px;">
                    <img alt="logo" style="width: 250px" src="../assets/Logo-LeeLee.png">
                  </div>
                  <h1 data-aos="zoom-in" data-aos-delay="600" style="font-size: 35px;" class="m-5 text-muted">
                    There should not be any child in our schools that does not know how to read effectively in spanish after first grade
                  </h1>
                  <div data-aos="zoom-in" data-aos-delay="800" class="text-center mt-5">
                    <button @click="onVideo" class="btn btn-danger color-primary-background btn-lg rounded-0 mx-2" >See Video</button>
                    <button class="btn btn-outline-danger border-color-primary btn-lg rounded-0 mx-2">Discover more</button>
                  </div>
                </div>
              </div>
            </div>
            <div data-aos="fade" class="col-lg-7 text-center">
              <div v-if="false" class="mt-5 rounded-pill">
                <img class="img-slide w-100 shadow-custom" src="../assets/imagen5.9ff47db1.jpg">
              </div>
              <div data-aos="fade" v-if="true" class="mt-5 rounded-pill">
                <img class="img-slide w-100 rounded" src="../assets/Child.png">
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div v-if="!change">
      <ViewSliderFirtScreen></ViewSliderFirtScreen>
    </div>
    <div v-if="ShowVideo" class="Video">
      <ViewVideoScreen v-if="ShowVideo"></ViewVideoScreen>
    </div>
  </div>
<!--  <button @click="onChangeSlide">change</button>-->

</template>

<script>
import ViewSliderFirtScreen from "@/views/ViewSliderFirtScreen.vue";
import ViewVideoScreen from "@/views/ViewVideoScreen.vue";


export default {
  name: "ViewFirstScreen",
  components: {ViewVideoScreen, ViewSliderFirtScreen},
  data : () => ({
      change : true,
      ShowVideo : false
  }),
  methods : {
      onChangeSlide() {
        this.change = !this.change
      },
      onVideo() {
        this.ShowVideo = !this.ShowVideo
      }
    }
  }
</script>

<style scoped>

    .color-primary-background {
      background-color: #e0602d;
      border-color: #e0602d;
    }
    .border-color-primary {
      border-color: #e0602d;
      color: #e0602d;
    }

    .ViewFirstScreen {
   /*   height: 100vh;*/
    }

    .background-img {
      background-attachment: fixed;
      background-position: center;
      background-repeat: no-repeat;
      background-size: cover;
      background-color: black;
      min-height: 100vh;
      padding-top: 20vh;
      background-image: url("../assets/imagen5.9ff47db1.jpg");
    }
    .img-slide {
      background-attachment: fixed;
      background-position: center;
      background-repeat: no-repeat;
      width: 95vh;
    }
    .background-color {
      background-image: linear-gradient(180deg, rgba(255,255,255, 0.01), rgba(255,255,255, 1) 85%),radial-gradient(ellipse at top left, rgba(13,110,253, 0.5), transparent 50%),radial-gradient(ellipse at top right, rgba(255,228,132, 0.5), transparent 50%),radial-gradient(ellipse at center right, rgba(255,228,132, 0.5), transparent 50%),radial-gradient(rgba(214,51,132, 0.5),transparent 50%);
      /*      background-image: url("../assets/App.jpg");*/
    }
    .shadow-custom {
      box-shadow: 13px 13px gray;
    }
/*    .adjust-image {
      height: 50vh;
    }
    .hex-background {
      width: 350px; !* container height - (border thickness * 2) *!
      height: 230px; !* container height - (border thickness * 2) *!
      border-radius: 1em/.5em;
      -webkit-clip-path: polygon(0% 50%, 25% 0%, 75% 0%, 100% 50%, 75% 100%, 25% 100%);
      -moz-clip-path: polygon(0% 50%, 25% 0%, 75% 0%, 100% 50%, 75% 100%, 25% 100%);
    }
    .background-effect {
      border-radius: 0% 0% 48% 48% / 14% 1% 14% 14%;
      background: radial-gradient(circle, rgba(64,186,184,1) 0%, rgba(43,95,167,1) 57%, rgba(0,0,0,1) 100%);
    }
/*

    .ViewFirstScreen {
/*      border-radius: 0% 0% 48% 48% / 14% 1% 14% 14%;*/

   /*   background-repeat: no-repeat;
      background-position: center;*/
     /* background: rgb(64,186,184);*/

    /*  background: radial-gradient(circle, rgba(64,186,184,1) 0%, rgba(43,95,167,1) 57%, rgba(0,0,0,1) 100%);
    }*/
    .effect-glass {
      backdrop-filter: blur(3px);
      background-color: #B6B6B626;
      z-index: 1000;
      position: relative;
    }
</style>
