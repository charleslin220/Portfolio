<template>
  <div class="homePage"></div>
</template>

<script lang="ts">
export default {
    name: 'HomeMain',
    props: {
        tab: {
            type: String,
            default: 'education'
        }
    },
    data () {
        return {
            currentTab: 'education'
        }
    },
    mounted (){
        this.currentTab = this.tab
    },
    updated () {
        this.currentTab = this.tab
        console.log(this.currentTab)
    }
}
</script>
