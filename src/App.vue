<script>
import AppBanner from "./components/AppBanner.vue";

export default {
  components: {
    AppBanner
  },

  data(){
    return {
      title: "ciao"
    }
  }
}
</script>

<template>
  <h1>{{ title }}</h1>
  <AppBanner />
</template>

<style>
</style>