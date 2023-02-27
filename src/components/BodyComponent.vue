<template>
    <ViewFirstScreen></ViewFirstScreen>
    <ViewTempScreen></ViewTempScreen>
<!--    <ViewFourScreen></ViewFourScreen>-->
    <ViewAboutScreen></ViewAboutScreen>

</template>

<script>
import ViewFirstScreen from "@/views/ViewFirstScreen.vue";
import ViewSecondScreen from "@/views/ViewSecondScreen.vue";
import ViewThreeScreen from "@/views/ViewThreeScreen.vue";
import ViewFourScreen from "@/views/ViewFourScreen.vue";
import ViewTempScreen from "@/views/ViewTempScreen.vue";
import ViewAboutScreen from "@/views/ViewAboutScreen.vue";

export default {
  name: "BodyComponent",
  components: {ViewAboutScreen, ViewTempScreen, ViewFourScreen, ViewThreeScreen, ViewSecondScreen, ViewFirstScreen}
}
</script>

<style scoped>

</style>
