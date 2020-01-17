<template>
  <section class="container">
    <div>
      <app-logo />Home
    </div>
  </section>
</template>

<script>
import AppLogo from "~/components/AppLogo.vue";

export default {
  components: {
    AppLogo
  },
  metaInfo: {
    title: "Home!!",
    titleTemplate: "%s - Ol~Yay!!!!!",
    htmlAttrs: {
      lang: "ko",
      amp: true
    }
  }
};
</script>

<style>
</style>

