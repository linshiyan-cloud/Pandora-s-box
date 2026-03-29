<template>
  <div id="app">
    <Header />
    <router-view />
  </div>
</template>

<script setup>
import Header from './components/Header.vue'
</script>

<style>
/* 全局重置，只做最基础的清理，不影响滚动！ */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html, body {
  width: 100%;
  height: auto;     /* 👈 修复：恢复滚动 */
  overflow: visible; /* 👈 修复：恢复滚动 */
  font-family: 'Segoe UI', Roboto, sans-serif;
}

#app {
  width: 100%;
  height: auto;     /* 👈 修复：不固定高度 */
  overflow: visible; /* 👈 修复：不锁住页面 */
  display: block;  /* 👈 修复：不使用弹性布局，不影响页面结构 */
}
</style>