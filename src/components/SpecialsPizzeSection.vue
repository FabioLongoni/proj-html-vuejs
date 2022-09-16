<template>
  <div class="section__component flex">
    <div class="section__img">
      <img src="../assets/img/h1-img-7n.png" alt="">
    </div>
    <div class="specials__pizza">
      <h2 class="text__up">
        specials*
      </h2>
      <p class="specials__info">Lorem, ipsum dolor sit amet consectetur ing elimpore exercitationem quasi impedit ?</p>
      <ul>
        <li>
          <span class="price">$10</span>
          <h3 class="pizza__name text__up">combo piccolo</h3>
          <p class="ingredients">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Recusandae, at.</p>
        </li>
        <li>
          <span class="price">$20</span> 
          <h3 class="pizza__name text__up">combo mezzo</h3>
          <p class="ingredients">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Maxime magni cum</p>
        </li>
        <li>
          <span class="price">$30</span> 
          <h3 class="pizza__name text__up">combo grande</h3>
          <p class="ingredients">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Perferendis, commodi.</p>
        </li>
      </ul>
    </div>
  </div>

</template>

<script>
export default {

}
</script>

<style scoped lang="scss">

  .section__component {
    padding-bottom: 0.5rem;
    color: #767676;
    .specials__pizza {
    flex-basis: 50%;
    padding: 5rem 8rem;
      h2 {
        color: #303030;
        
      }
      .specials__info {
        margin-top: 13px;
        font-size: 18px;
        line-height: 1.556em;
        padding-bottom: 23px;
      }
      p {
        padding-top: 7px;
      }
      h3 {
        display: inline;
        font-size: 25px;
        line-height: 1.4;
        color: #303030;
      }
      .price {
        font-family: Oswald,sans-serif;
        font-size: 25px;
        line-height: 1.4em;
        letter-spacing: .05em;
        padding-right: 16px;
        color: #ab4027;
        font-weight: 500;
      }
      li {
        margin-bottom: 19px;
      }
    }
    .section__img {
    background-image: url(../assets/img/h1-img-4.jpg);
    background-size: cover;
    background-position: center;
    flex-basis: 50%;
    padding-bottom: 0.5rem;
      img {
        transform: scale(0.7);
      }
    }
    .ingredients {
      margin-left: 3.75rem;
    }
  }
  
  
</style>