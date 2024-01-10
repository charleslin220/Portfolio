<template>
  <div class="homePage"></div>
  <div v-if="currentTab === 'education'">education</div>
  <div v-else-if="currentTab === 'career'">career</div>
  <div v-else-if="currentTab === 'personal'">personal</div>
  <div v-else-if="currentTab === 'game'">game</div>
</template>

<script lang="ts">
export default {
  name: "HomeMain",
  props: {
    tab: {
      type: String,
      default: "education",
    },
  },
  data() {
    return {
      currentTab: "education",
    };
  },
  mounted() {
    this.currentTab = this.tab;
  },
  updated() {
    this.currentTab = this.tab;
    console.log(this.currentTab);
  },
};
</script>
