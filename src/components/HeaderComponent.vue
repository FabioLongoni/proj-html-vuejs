<template>
  <div class="main__header">
    <div class="header__component flex a__center">
      <div>
        <button class="btn">order online</button>
      </div>
      <div>
        <ul class="flex a__center main__nav">
          <li>
            <a href="#">home</a>
          </li>
          <li>
            <a href="#">pages</a>
          </li>
          <li>
            <a href="#">menù</a>
          </li>
          <li>
            <a href="#"><img class="header__logo" src="../assets/img/h5-logo-divided-header.png" alt=""></a>
          </li>
          <li>
            <a href="#">event</a>
          </li>
          <li>
            <a href="#">blog</a>
          </li>
          <li>
            <a href="#">landing</a>
          </li>   
        </ul>
      </div>
      <div class="search__nav">
        <ul class="flex ul__search__nav">
          <li>
            <a href="#">cart</a>
          </li>
          <li>
            <a href="#">search</a>
          </li>
        </ul>
      </div>
    </div>
    <div class="header__jumbotron">
      <img src="../assets/img/h3-rev-img-6.png" alt="">
    </div>
  </div>
  
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
  @import '../style/_variables';
  @import '../style/header';
</style>