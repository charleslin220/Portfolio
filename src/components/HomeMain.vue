<template>
  <div class="homePage"></div>
  <div v-if="currentTab === 'education'">
    <a href=""></a>

</div>
  <div v-else-if="currentTab === 'career'"></div>
  <div v-else-if="currentTab === 'personal'"></div>
  <div v-else-if="currentTab === 'game'"></div>
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
