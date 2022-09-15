<template>
  <div id="app">
    <HeaderComponent/>
    <MainComponent/>
    <FooterComponent/>
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
import MainComponent from './components/MainComponent.vue';
import "@fontsource/oswald";
import "@fontsource/oswald/500.css"



export default {
  name: 'App',
  components: {
    HeaderComponent,
    FooterComponent,
    MainComponent
  }
}
</script>

<style lang="scss">
@import './style/mainStyle';
@import './style/_variables';
</style>
