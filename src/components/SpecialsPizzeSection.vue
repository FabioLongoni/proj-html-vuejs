<template>
  <div class="section__component flex">
    <div class="section__img">
    </div>
    <div class="specials__pizza">
      <h2 class="text__up">
        specials
      </h2>
      <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Est, dolor possimus. Rem similique tempore exercitationem quasi impedit ?</p>
      <ul>
        <li>
          <span class="price">$10</span>
          <h3 class="pizza__name text__up">combo piccolo</h3>
          <p class="ingredient">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Recusandae, at.</p>
        </li>
        <li>
          <span class="price">$20</span> 
          <h3 class="pizza__name text__up">combo mezzo</h3>
          <p class="ingredient">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Maxime magni cum</p>
        </li>
        <li>
          <div class="price">$30</div> 
          <h3 class="pizza__name text__up">combo grande</h3>
          <p class="ingredient">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Perferendis, commodi.</p>
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
    .specials__pizza {
    flex-basis: 50%;
    padding: 5rem 7rem;
      h2 {
        color: #303030;
      }
    }
    .section__img {
    background-image: url(../assets/img/h1-img-4.jpg);
    flex-basis: 50%;
    padding-bottom: 0.5rem;
    }
  }
  
  
</style>