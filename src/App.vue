<template>
  <div id="app">
    <v-main>
      <div class="main-screen">
        <side-bar />
        <main-container />
      </div>
    </v-main>
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
  data: () => ({
    //
  }),
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background: linear-gradient(to bottom right, #cfe6ff, #fff0fa);
  background-repeat: no-repeat;
  background-size: 100%;
  height: 100vh;
}
.main-screen {
  display: flex;
  flex-direction: row;
  margin: 3rem;
  background-color: rgba(255, 255, 255, 0.6);
  border-radius: 1rem;
}
</style>
