<template>
  <div class="contact">
      <h1>This is an contact page</h1>
      <InputContact />
      <textAreaContact />
      <ButtonContact />
      <AllFooter />
  </div>
</template>

<script>
import InputContact from '@/components/InputContact.vue';
import textAreaContact from '@/components/textAreaContact.vue';
import ButtonContact from '@/components/ButtonContact.vue';
import AllFooter from '@/components/AllFooter.vue';
export default {
    name: "contact",
    components: {
    InputContact,
    textAreaContact,
    ButtonContact,
    AllFooter,
  }
}
</script>

<style>

</style>