<template>
  <div class="btn-container">
    <icon-arrow-left
      class="arrow-icon"
      :width="24"
      :height="24"
      :color="iconColor"
    ></icon-arrow-left>
    <icon-arrow-right
      class="arrow-icon"
      :width="24"
      :height="24"
      :color="iconColor"
    ></icon-arrow-right>
  </div>
</template>

<script>
import IconArrowLeft from './icons/IconArrowLeft.vue';
import IconArrowRight from './icons/IconArrowRight.vue';
export default {
  name: 'HistoryButton',
  components: { IconArrowLeft, IconArrowRight },
  data() {
    return {
      iconColor: '#959BA5',
    };
  },
};
</script>

<style lang="scss" scoped>
.btn-container {
  display: flex;
  flex-direction: row;
  gap: 1rem;
}
</style>
