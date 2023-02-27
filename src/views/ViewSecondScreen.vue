<template>
    <div class="ViewSecondScreen mt-5">
      <div class="">
        <h1 class="text-center my-5">
          PLATFORMS
        </h1>
        <div class="bg-success">
          <div class="row">
            <div class="col">
              <div data-aos="fade-right">
                <div class="card-android">
                </div>
              </div>
            </div>
            <div class="col">
              <div class="text-card-custom text-white text-center">
                <h1>ANDROID</h1>
              </div>
            </div>
          </div>
        </div>
        <div class="bg-secondary">
          <div class="row">
            <div class="col">
              <div class="text-card-custom2 text-white text-center">
                <h1>IOS</h1>
              </div>
            </div>
            <div class="col">
              <div data-aos="fade-left">
                <div  class="card-ios">
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="bg-primary">
          <div class="row">
            <div class="col">
              <div data-aos="fade-right">
                <div  class="card-web">
                </div>
              </div>
            </div>
            <div class="col">
              <div class="text-card-custom3 text-white text-center">
                <h1>WEB</h1>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

</template>

<script>
export default {
  name: "ViewSecondScreen"
}
</script>

<style scoped>
  .ViewSecondScreen {
    background-color: white;
  }
  .card-android {
    height: 50vh;
    backdrop-filter: blur(5px);
    background-image: url("../assets/AppScreen3.jpg");
    -webkit-clip-path:polygon(-19% 71%, 36% 1%, 118% 0%, 100% 70%, 75% 100%, 25% 100%);
    clip-path:polygon(-19% 71%, 36% 1%, 118% 0%, 100% 70%, 75% 100%, 25% 100%);
    background-repeat: no-repeat;
    background-position: center;
    text-align: center;
  }
  .card-ios {
  /*  top: -82px;
    position: relative;*/
    height: 50vh;
    -webkit-clip-path: polygon(-80% 51%, 0% 14%, 659% 76%, 104% 76%, -3% 87%, 15% 95%);
    clip-path: polygon(-80% 51%, 0% 14%, 659% 76%, 104% 76%, -3% 87%, 15% 95%);
    background-image: url("../assets/AppScreen.jpg");
    background-repeat: no-repeat;
    background-position: center;

  }
  .card-web {
/*    top: -165px;
    position: relative;*/
    height: 50vh;
    -webkit-clip-path:polygon(-19% 71%, 36% 1%, 118% 0%, 100% 70%, 75% 100%, 25% 100%);
    clip-path:polygon(-19% 71%, 36% 1%, 118% 0%, 100% 70%, 75% 100%, 25% 100%);
    background-image: url("../assets/AppScreen2.jpg");
    background-repeat: no-repeat;
    background-position: center;
  }
  .text-card-custom {
    /*background-color: rgba(45,127,74,0.83);*/
    height: 100%
  }
  .text-card-custom2 {
/*    background-color: rgba(119, 136, 153, 0.82);*/
    height: 100%
  }
  .text-card-custom3 {
    /*background-color: rgba(30, 144, 255, 0.85);*/
    height: 100%
  }

</style>
