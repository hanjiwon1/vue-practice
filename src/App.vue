<template>
  <div id="app">
    <div class="main-screen">
      <side-bar />
      <main-container />
    </div>
  </div>
</template>

<script>
import SideBar from './Layout/SideBar/SideBar.vue';
import MainContainer from './Layout/MainContainer/MainContainer.vue';

export default {
  name: 'App',
  components: {
    SideBar,
    MainContainer,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.main-screen {
  display: flex;
  flex-direction: row;
  margin: 3rem;
  background-color: rgba(255, 255, 255, 0.6);
  border-radius: 1rem;
}
</style>
