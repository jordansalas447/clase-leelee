<template>
  <div v-if="false" data-aos="fade-left" class="ViewAboutScreen bg-white text-center">
    <div class="Video">
      <div class="bg-dark text-white text-end p-2">
        <button class="btn text-white">
          X
        </button>
      </div>
      <div class="container">
        <img src="../assets/vission.28a2a0e2.png">
        <h2>
          <strong>Mission</strong>
        </h2>
        <p>Our mission is to provide educational solutions oriented in providing support to teachers in achieving
          innovative pedagogical methods, and students reach substantive learning in optimal time.
        </p>
        <img src="../assets/mission.fce69676.png">
        <h2>
          <strong>Vision</strong>
        </h2>
        <p>
          Learning to read is like reaching an invaluable treasure. Our application LeeLee will allow millions of students to achieve this valued treasure.
          There should not be any child in our schools that does not know how to read effectively after first grade.
        </p>
      </div>
      <FooterComponent></FooterComponent>
    </div>
  </div>
</template>

<script>
import FooterComponent from "@/components/FooterComponent.vue";

export default {
  name: "ViewAboutScreen",
  components: {FooterComponent}
}
</script>

<style scoped>
.ViewAboutScreen {
  width: calc(100% - 100px);
  overflow:auto;
  display: inline-block;
  position: absolute;
  height: 100vh;
  z-index: 3000;
  top: 0;
  right: 0;
}

</style>
