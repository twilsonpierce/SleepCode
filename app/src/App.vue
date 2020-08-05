<template>
  <div id="app">
    <nav-bar></nav-bar>
    <left-section></left-section>
    <right-section></right-section>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import LeftSection from './components/LeftSection.vue'
import RightSection from './components/RightSection.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    LeftSection, 
    RightSection
  }
}
</script>

<style>
  #app {
     font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #000000;
    margin-top: 60px;
  }

</style>
