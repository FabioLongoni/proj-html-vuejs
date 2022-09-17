<template>
  <div class="form__wrapper">
    <form class="form flex">
      <div class="input flex a__center">
        <input type="number" min="1" max="10">
        <span class="font__o text__up font__500">for</span>
        <input type="date" value="today" />
        <span class="font__o text__up font__500">at</span>
        <input type="time" value="20:00">
      </div>
      <button id="book" class="btn">book a table</button>
    </form>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
  .form__wrapper {
    padding-bottom: 0.5rem;
    .form {
      background-image: url(../assets/img/h3-background-img-3.jpg);
      background-size: cover;
      padding: 5rem;
      gap: 3rem;
      justify-content: center;
      span {
        font-size: 20px;
        color: white;
      }
    }
  }
  input {
    padding: 1rem;
    height:50px;
    color: #858585;
    width: 200px;
    border: 1px solid #303030;
  }
  #book {
    height:50px;
    width: 200px;
  }
  .input {
    gap: 1rem;
  }
</style>