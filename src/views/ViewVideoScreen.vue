<template>
  <div v-if="close" data-aos="zoom-in" data-aos-delay="100" class="ViewVideScreen text-center px-4">
    <div class="Video">
      <div class="bg-dark text-white text-end border p-2">
        <button @click="OnClose" class="btn text-white">
          X
        </button>
      </div>
      <div class="">
        <iframe style="width: 100%;height: 80vh;" src="https://www.youtube-nocookie.com/embed/jsUke1XMmNk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
      </div>

    </div>
  </div>

</template>

<script>
export default {
  name: "ViewVideoScreen",
  data: () => ({
    close:true
  }),
  methods : {
    OnClose() {
        this.close = false
    }
  }
}
</script>

<style scoped>
    .Video {
      margin-top: 4vh;
    }

    .ViewVideScreen {
      backdrop-filter: blur(3px);
      height: 100vh;
      width: 100%;
      z-index: 3000;
      position: absolute;
      top: 0;
    }

</style>
