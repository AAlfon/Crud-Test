
<template>
  <main>
      <TopicList />
  </main>
</template>



<script>
  import TopicList from './components/TopicList.vue'
  export default {
    components: {
      TopicList
    }
  }
</script>
<style scoped>
  .content-container {
    widows: 100%;
    height: auto;
    background-color: azure;
  }
</style>
