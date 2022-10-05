
<template>
  <div id="app">
    <el-container>
      <el-header height="60px">
        <div><img src="./assets/loeey.png" alt="" /></div>
        <nav>
          <span><a href="">Me</a></span>
          <span><a href="">Blog</a></span>
          <span><a href="">Project</a></span>
          <i class="iconfont"> &#xe8a1;</i>
          <i class="iconfont">&#xe600;</i>
          <span></span>
        </nav>
      </el-header>
      <el-main>
        <router-view></router-view>
      </el-main>
      <el-footer><h1>还没想好要写什么</h1></el-footer>
    </el-container>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "app",
  components: {
    HelloWorld,
  },
};
</script>

<style >
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.el-header {
  display: flex;
  justify-content: space-between;
  padding-left: 0;
}
.el-header div {
  position: relative;
  width: 65px;
  height: 65px;
}
.el-header div img {
  position: absolute;
  width: 100%;
  height: 100%;
  top: 15px;
}
.el-header nav {
  line-height: 60px;
}
.el-header nav span,
i {
  margin: 0 30px;
}
.el-header nav i {
  font-size: 24px;
}

.el-main {
  background-color: #f7f7f7;
}
</style>
