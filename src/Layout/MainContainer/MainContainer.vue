<template>
  <main class="main-container">
    <div class="main-contents">
      <top-navagation></top-navagation>
      <feature-section></feature-section>
      <statistic-section></statistic-section>
    </div>
    <div class="side-contents">
      <user-profile></user-profile>
      <quick-link></quick-link>
    </div>
  </main>
</template>

<script>
import TopNavagation from '@/components/TopNavagation.vue';
import FeatureSection from '@/components/FeatureSection.vue';
import StatisticSection from '@/components/StatisticSection.vue';
import UserProfile from '@/components/UserProfile.vue';
import QuickLink from '@/components/QuickLink.vue';

export default {
  name: 'MainSection',
  components: {
    TopNavagation,
    FeatureSection,
    StatisticSection,
    UserProfile,
    QuickLink,
  },
  data() {
    return {};
  },
  methods: {},
};
</script>

<style lang="scss" scoped>
.main-container {
  padding: 2rem;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  width: 100%;
}
.main-contents,
.side-contents {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
</style>
