<template>
  <div class="team__partners__container">
    <div class="team flex">
    <a v-for="(slide,i) in slides" :key="i" href="slide.href"><img :src="slide.image" alt=""></a>
  </div>
  <div class="partners flex">
    <a v-for="(partner,i) in partners" :key="i" href="partner.href"><img :src="partner.image" alt=""></a>
  </div>
  </div>
  
</template>

<script>
export default {
  data() {
    return {
      slides: [
        {
          href: "#",
          image: require('../assets/img/h1-team-1a-700x900.jpg'),
        },
        {
          href: "#",
          image: require('../assets/img/h1-team-2a.jpg'),
        },
        {
          href: "#",
          image: require('../assets/img/h1-team-3a.jpg'),
        },
        {
          href: "#",
          image: require('../assets/img/h1-team-4a.jpg'),
        }  
      ],
      partners: [
        {
          href: "#",
          image: require('../assets/img/h1-clients-img-1.png'),
        },
        {
          href: "#",
          image: require('../assets/img/h1-clients-img-2.png'),
        },
        {
          href: "#",
          image: require('../assets/img/h1-clients-img-3.png'),
        },
        {
          href: "#",
          image: require('../assets/img/h1-clients-img-4.png'),
        },
        {
          href: "#",
          image: require('../assets/img/h1-clients-img-5.png'),
        }    
      ],

    
    }
  }
}
</script>

<style scoped lang="scss">
.team {
  padding-bottom: 0.5rem;
  a {
    display: inline-flex;
    flex-grow: 1;
    flex-basis: 0;
    img {
      object-fit: cover;
    }
  }
}
.partners {
  background-color: #f7f7f2;
  justify-content: center;
  padding: 3rem 0;
  a {
    display: inline-flex;
    img {
      object-fit: cover;
      width: 200px;
    }
  }
}
</style>