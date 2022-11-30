<!-- DECLARE, REGISTER, USE (COMPONENTS) -->

<template>
  <!-- THIS IS THE ONLY ID ALLOWED IN VUE.JS DO NOT USE THEM ANYWHERE ELSE -->
  <!-- WHEN IT 'MOUNTS' THIS APP ID IS WHAT IT LOOKS FOR, ITS IN THE MAIN.JS -->
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    
    <!-- 3. USE -->
    <!-- he recommends sticking to the casing, so just use camel case. -->
    <!-- its written like this because its a tag being translated and doesn't need a closing tag -->
    <!-- and we aren't putting content here since we already did it INSIDE the component -->
    <MyComponent/>
  </div>
</template>

<script>
// 1. DECLARE
// the @ is equivalent to stating the rest of the folders listed
import MyComponent from '@/components/MyComponent.vue';

export default {
  name: 'App',
  // add components and list them
  components: {
    // 2. REGISTER
    MyComponent
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
