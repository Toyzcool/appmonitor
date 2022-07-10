<template>
  <img alt="serve logo" src="./assets/logo.png">
  <h1>欢迎使用应用更新订阅服务</h1>
  <user-login />
</template>

<script>
import { defineComponent } from "vue";
import UserLogin from "@/components/UserLogin";

export default defineComponent({
  components: {
    UserLogin,
  },
});
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
