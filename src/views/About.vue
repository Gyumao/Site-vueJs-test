<template>
  <div class="about">
    <h1>This is an about page</h1>
    <BlockquoteAbout />
    <VideoAbout />
    <AllFooter />
  </div>
</template>

<script>
import BlockquoteAbout from '@/components/BlockquoteAbout.vue';
import VideoAbout from '@/components/VideoAbout.vue';
import AllFooter from '@/components/AllFooter.vue';
export default {
  name: "about",
  components: {
  BlockquoteAbout,
  VideoAbout,
  AllFooter,
  }
};
</script>

<style>
.about
{
  background: rgb(131,58,180);
  background: linear-gradient(90deg, rgba(131,58,180,1) 20%, rgba(253,29,29,1) 50%, rgba(252,176,69,1) 80%);
  text-shadow: 2px 2px black;
}
</style>
