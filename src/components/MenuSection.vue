<template>
  <div class="menu__container">
    <div class="title">
      <span class="text__up font__500 font__o">choose your flavor</span>
      <h2 class="text__up">the best pizza menu un town</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Corporis corrupti labore officiis eum, illum sit recusandae eius velit animi quos.</p>
    </div>
    <div class="pizze">
      <ul class="pizze__wrapper flex">
        <li v-for="(pizza,i) in pizze" :key="i" class="pizza__card">
          <a href="pizza.href">
            <img :src="pizza.image" alt="">
            <h4 class="pizza__name text__up font__o font__500">{{pizza.name}}</h4>
            <span class="price font__o">{{pizza.price}}</span>
          </a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      pizze: [
        {
          href: "#",
          image: require('../assets/img/h3-product-img-1a-100x100.png'),
          name: 'fiori di zucca',
          price: '$7.00 - 50.00'
        },
        {
          href: "#",
          image: require('../assets/img/h3-product-img-2a-150x150.png'),
          name: 'campagnola',
          price: '$50.00 - 95.00'
        },
        {
          href: "#",
          image: require('../assets/img/h3-product-img-3a-150x150.png'),
          name: 'bismarck',
          price: '$30.00'
        },
        {
          href: "#",
          image: require('../assets/img/h3-product-img-4a-150x150.png'),
          name: 'valdostana',
          price: '$55.00'
        },
        {
          href: "#",
          image: require('../assets/img/h3-product-img-5a-150x150.png'),
          name: 'pizza tartufata',
          price: '$45.00'
        },
        {
          href: "#",
          image: require('../assets/img/h3-product-img-6a-100x100.png'),
          name: 'francescana',
          price: '$25.00'
        }        
      ],

    
    }
  }
}
</script>

<style scoped lang="scss">
.menu__container {
  padding: 7rem 0;
  .title {
    text-align: center;
    max-width: 600px;
    margin: 0 auto;
    h2 {
      padding: 1rem;
      color: #303030;
    }
    span {
      font-size: 12px;
      line-height: 1.375em;
      letter-spacing: .2em;
      color: #d2401e;
    }
    p {
      font-size: 18px;
      line-height: 1.556em;
      color: #5a5a5a;
    }
  }

  .pizze {
    padding-top: 3rem;
    overflow: hidden;
    .pizza__card {
      text-align: center;
      flex-basis: 0;
      flex-grow: 1;
      img {
        width: 180px;
      }
      .pizza__name {
        letter-spacing: 0.1em;
        color: #d2401e;
      }
    }
    .pizze__wrapper {
      gap: 5rem;
      margin-left: -90px;
    }
  }
  
}

</style>