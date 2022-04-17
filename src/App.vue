<template>
  <div id="app">
    <NavigationBar/>
    <MainSection/>
    <HelloWorld msg="Welcome !"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import NavigationBar from './Layout/NavigationBar/NavigationBar.vue'
import MainSection from './Layout/MainSection/MainSection.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    NavigationBar,
    MainSection,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
