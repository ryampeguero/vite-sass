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
  <h1 class="bg-black">{{ title }}</h1>
  <AppBanner />
  <h2>Prova</h2>
</template>

<style>
.bg-black {
  background-color: black;
  color: white;
}

h2{
  color: red;
}
</style>