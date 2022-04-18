<template>
  <div class="navigation-container">
    <history-button></history-button>
    <div>방가방가</div>
  </div>
</template>

<script>
import HistoryButton from './HistoryButton.vue';
export default {
  name: 'top-navagation',
  components: {
    HistoryButton,
  },
};
</script>

<style>
.navigation-container {
  margin: 1rem;
  color: black;
  display: flex;
  align-items: center;
}
</style>
