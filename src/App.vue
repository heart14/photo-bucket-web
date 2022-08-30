<template>
  <div id="app">
    <div>
      <PhotoUpload />
    </div>
  </div>
</template>

<script>
import PhotoUpload from "./view/PhotoUploadPage/PhotoUpload.vue";

export default {
  name: "App",
  components: {
    PhotoUpload,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
