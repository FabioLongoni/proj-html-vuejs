<template>
  <div class="slogan__section">
    <div class="carousel flex">
      <a v-for="(card,i) in cards" :key="i" href="card.href"><img :src="card.image" alt=""></a>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      cards: [
        {
          href: "#",
          image: require('../assets/img/h3-img-1.jpg'),
        },
        {
          href: "#",
          image: require('../assets/img/h3-img-2.jpg')
        },
        {
          href: "#",
          image: require('../assets/img/h3-img-3.jpg')
        },
        {
          href: "#",
          image: require('../assets/img/h3-img-4.jpg')
        }  
      ],

    
    }
  }
}
</script>

<style scoped lang="scss">

</style>