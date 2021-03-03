<template>
  <div id="app">
    <div><p style="color: #2285ff"> 这里是主模块 </p></div>
    <Project1 />
    <HelloWorld />
  </div>
</template>

<script>
import Project1 from '@/lib/src/components/Project1'
import HelloWorld from '@/submodule2/src/components/HelloWorld'

export default {
  name: 'App',
  components: {
    Project1,
    HelloWorld,
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
