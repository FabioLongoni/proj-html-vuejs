<template>
  <div class="slogan__section">
    <div class="slogan__slides flex">
      <a v-for="(slide,i) in slides" :key="i" href="slide.href"><img :src="slide.image" alt=""></a>
    </div>
    <div class="slogan__text">
      <div class="slogan__text__content">
        <font-awesome-icon class="quote" icon="fa-solid fa-quote-left" />
        <p class="cit">
          “Forget the trendy pizza shops, This hidden spot makes the best New York-style pizza slice in naples”
        </p>
        <p class="font">washington post 2018</p>
        <font-awesome-icon class="circle" icon="fa-solid fa-circle" />
        <font-awesome-icon class="circle" icon="fa-solid fa-circle" />
        <font-awesome-icon class="circle" icon="fa-solid fa-circle" />
      </div>
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
  .slogan__section {
    padding: 0.5rem 0;
    .slogan__slides {
      gap: 0.5rem;
      padding-bottom: 0.5rem;
      a {
        display: inline-flex;
        flex-grow: 1;
        flex-basis: 0;
      }
    }
  }
  .slogan__text__content {
    max-width: 800px;
    margin: 0 auto;
    text-align: center;
    font-family: "Oswald", sans-serif;
    text-transform: uppercase;
    font-weight: 500;
    padding: 6rem 0;
    .cit {
      font-size: 25px; 
      color: #303030;   
      letter-spacing: .05em;
      line-height: 1.48em;  
    }
    .quote {
      height: 60px;
      color: #b7903c;
      padding-bottom: 1.5rem;
    }
    .font {
      line-height: 1.375em;
      letter-spacing: .2em;
      color: #b7903c;
      padding: 0.75rem 0 1.2rem;
      font-size: 12px;
    }
    .circle {
      color: #e4e4d4;
      padding: 0 0.2rem;
      font-size: 10px;
    }
    .circle:hover {
      color: #b7903c;
    }
  }
  .slogan__text {
      background-image: url(../assets/img/h3-testimonials-bckgrnd.jpg);
      background-size: cover;
      background-repeat: no-repeat;
      background-position: center;
  }
</style>