<template>
  <section class="container">
    <div>About</div>
  </section>
</template>

<script>
import AppLogo from "~/components/AppLogo.vue";

export default {
  components: {
    AppLogo
  },
  metaInfo: {
    title: "About!!",
    titleTemplate: "%s - Yay!!!!!",
    htmlAttrs: {
      lang: "ko",
      amp: true
    }
  }
};
</script>

<style>
</style>

