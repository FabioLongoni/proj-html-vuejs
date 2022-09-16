<template>
  <div class="jumbotron">
    <div class="container">
      <h2 class="text__up">
        go ahead and <br>
        build your <br>
        own pizza <br>
        we won't <br>
        judge
      </h2>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
@import '../style/_variables';

  .jumbotron {
    background-image: url(../assets/img/h3-background-img.jpg);
    margin-bottom: 0.5rem;
    background-size: 1100px 320px;
    background-repeat: repeat;
    background-position: center;
    .container {
      max-width: 800px;
      margin: 0 auto;
      padding: 6rem 0;
      h2 {
        font-size: 70px;
        line-height: 75px;
        font-weight: 500;
        color: $color-white;
      }
    }
  }
</style>