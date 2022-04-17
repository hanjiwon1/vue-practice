<template>
  <div>
    <div class="hi-there" v-for="(elem, i) in products" :key="i">
      <img src="../../assets/logo.png">
      <h4>{{ elem }} 원룸</h4>
      <p>{{ price[i] }} 만원</p>
      <button @click="신고[i]++">허위매물 신고</button>
      <span>신고 : {{ 신고[i] }}</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NameSection',
  data () {
    return {
      products: ['역삼동', '천호동', '마포구'],
      price: [60, 70, 80],
      신고: [0, 0, 0],
    }
  },
  methods: {
    
  },
}
</script>

<style lang="scss">
  .hi-there {
    margin-top: 3rem;
  }
</style>