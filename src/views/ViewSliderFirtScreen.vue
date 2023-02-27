<template>
  <div class="ViewFirstScreen text-white ">
    <div class="background-img text-center zoom-in-out-box">
      <div class="effect-glass container rounded">
        <div class="p-5">
          <h1 data-aos="zoom-in" data-aos-delay="200" style="font-size: 50px" class="">
            <strong>LEE LEE</strong>
          </h1>
          <h2 data-aos="zoom-in" data-aos-delay="600" style="font-size: 35px" class="m-5">
            THERE SHOULD NOT BE ANY CHILD IN OUR SCHOOLS THAT DOES NOT KNOW HOW TO READ EFFECTIVELY IN SPANISH AFTER FIRST GRADE
          </h2>
          <div data-aos="zoom-in" data-aos-delay="800" class="text-center mt-5">
            <button class="btn btn-outline-light btn-lg rounded-0 mx-2" >See Video</button>
            <button class="btn btn-outline-light btn-lg rounded-0 mx-2">Discover more</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ViewSliderFirtScreen"
}
</script>

<style scoped>
.background-img {
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  background-color: black;
  min-height: 100vh;
  padding-top: 18vh;
  background-image: url("../assets/imagen5.9ff47db1.jpg");
}

.adjust-image {
  height: 50vh;
}
.hex-background {
  width: 350px; /* container height - (border thickness * 2) */
  height: 230px; /* container height - (border thickness * 2) */
  border-radius: 1em/.5em;
  -webkit-clip-path: polygon(0% 50%, 25% 0%, 75% 0%, 100% 50%, 75% 100%, 25% 100%);
  -moz-clip-path: polygon(0% 50%, 25% 0%, 75% 0%, 100% 50%, 75% 100%, 25% 100%);
}
.background-effect {
  border-radius: 0% 0% 48% 48% / 14% 1% 14% 14%;
  background: radial-gradient(circle, rgba(64,186,184,1) 0%, rgba(43,95,167,1) 57%, rgba(0,0,0,1) 100%);
}

.ViewFirstScreen {
}
.effect-glass {
  backdrop-filter: blur(3px);
  background-color: #00000026;
  width: 80%;
  z-index: 1000;
  position: relative;
}
</style>
