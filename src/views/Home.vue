<template>
  <div class="home">
  <h1 class h1-home> Site Vue Test</h1>
  <HomeImage />
  <AllFooter />
  </div>
</template>

<script>
import HomeImage from '@/components/HomeImage.vue';
import AllFooter from '@/components/AllFooter.vue';

export default {
  name: "home",
  components: {
    HomeImage,
    AllFooter,
    
  }
};
</script>

<style>

</style>