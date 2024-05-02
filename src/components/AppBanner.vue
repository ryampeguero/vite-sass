<script>
export default {
  data(){
    return {
      imageName: "05",
      natureImage: ""
    }
  },

  methods: {
    getImageUrl(imageName){
      return new URL(`../assets/img/${imageName}.webp`, import.meta.url).href
    },
  }
}
</script>

<template>
  <div class="banner">
    <h2 class="bg-black">Titolo</h2>
    <!-- <img src="/img/03.webp" alt="">
    <img src="../assets/img/04.webp" alt=""> -->
      <!-- <img :src="getImageUrl(imageName)" alt=""> -->
  </div>
</template>


<style scoped>
.banner {
  height: 60vh;
  background-color: lightblue;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

h2{
  color: greenyellow;
}

</style>