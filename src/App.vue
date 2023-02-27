<script setup>
/* import { RouterLink, RouterView } from 'vue-router' */
import NavbarComponent from "@/components/NavbarComponent.vue";
import BodyComponent from "@/components/BodyComponent.vue";
import FooterComponent from "@/components/FooterComponent.vue";
import AOS from 'aos';

AOS.init();
</script>

<template>
  <header>
    <div class="wrapper">
    <NavbarComponent></NavbarComponent>
    <BodyComponent></BodyComponent>
    <FooterComponent></FooterComponent>
<!--    <ViewAboutScreen></ViewAboutScreen>-->
<!--      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>-->
    </div>
  </header>
  <RouterView />
</template>

<style scoped>

</style>
