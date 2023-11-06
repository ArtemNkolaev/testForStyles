<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <ClassStyles/>
  <InlineStyles/>
  <CompStyle/>
  <ProgressLine/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import ClassStyles from './components/ClassStyles.vue';
import InlineStyles from './components/InlineStyles.vue';
import CompStyle from './components/CompStyle.vue';
import ProgressLine from './components/Progress.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    InlineStyles,
    CompStyle,
    ClassStyles,
    ProgressLine
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
