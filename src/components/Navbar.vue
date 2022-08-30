<template>
  <div class="head">
      <div class="logo"><img alt="Vue logo" src="@/assets/logo.png" /></div>
      <div class="title"><h1>Photo Bucket</h1></div>
    </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style scoped>
.head{
    background-color: #f6f5ec;
    height: 50px;
    line-height: 50px;
}
.logo{
    position: fixed;
    float: left;
}
img{
    width: 40px;
    height: 40px;
    padding: 5px;
    padding-left: 25px;
}
</style>