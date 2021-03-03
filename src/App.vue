<template>
  <div id="app">
    <div><p class="font-color: pink"> 这里是主模块 </p></div>
    <!-- <Project1 /> -->
  </div>
</template>

<script>
// import Project1 from '@/submodule1/src/components/Project1.vue'

export default {
  name: 'App',
  components: {
    // Project1,
  }
}
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
