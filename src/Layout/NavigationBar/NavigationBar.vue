<template>
  <div class="navbar-container">
    <ul>
      <li>안녕 나 NavBar야 ! </li>
    </ul>
  </div>
</template>
<script>
export default {
  name: 'NavigationBar',

}
</script>
<style lang="scss" scoped>
  .navbar-container {
    background-color: rgb(26, 35, 70);
  }
  ul {
    height: 5rem;
    display: flex;
    justify-content: center;
    align-items: center;
    li {
      color: white;
    }
  }
</style>