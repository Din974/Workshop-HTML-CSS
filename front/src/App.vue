<template>
  <div id="app">
    <HeaderBar/>
    <router-view/>
  </div>
</template>

<script>
  import HeaderBar from '@/components/HeaderBar.vue';
export default {
  components: {
    HeaderBar,
  },
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@1,900&display=swap');
</style>
