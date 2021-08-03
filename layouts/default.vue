<template lang="pug">
  .app
    Header
    nuxt
    Footer
</template>

<script lang="ts">
import Header from "~/components/Header.vue";
import Footer from "~/components/Footer.vue";

export default {
  components: {
    Header,
    Footer
  }
}
</script>

