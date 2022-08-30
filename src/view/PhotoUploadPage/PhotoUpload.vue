<template>
  <div>
    <Navbar />
  </div>
</template>

<script>
import Navbar from "../../components/Navbar.vue";

export default {
  name: "PhotoUpload",
  components: {
    Navbar,
  },
};
</script>

<style scoped>
.logo {
  float: left;
  margin: 0;
}
.title {
  margin: 0;
}
</style>