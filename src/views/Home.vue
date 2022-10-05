<template>
  <div class="home">
    <div class="logo">
      <img alt="Vue logo" src="../assets/logo.jpg" />
    </div>
    <HelloWorld msg="Welcome to Loeey's Blog" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
  },
};
</script>

<style scoped>
/* 头像 */
.logo {
  width: 130px;
  height: 130px;
  border: 1px solid #eee;
  border-radius: 50%;
  margin: 0 auto;
}
img {
  width: 100%;
  height: 100%;
  border-radius: 50%;
}
</style>