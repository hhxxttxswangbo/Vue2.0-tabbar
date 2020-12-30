<template>
  <div id="app">
    <!-- 勿忘 <router-view></router-view> -->
    <router-view></router-view>
    <main-tab-bar></main-tab-bar>
  </div>
</template>

<script>
import MainTabBar from "./components/MainTabBar";
export default {
  components: {
    MainTabBar,
  },
};
</script>

<style>
@import "./assets/css/base.css";
</style>