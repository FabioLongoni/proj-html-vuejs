<template>
  <div id="app">
    <HeaderComponent/>
    <MainComponent/>
    <FormComponent />
    <FooterComponent/>
    
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
import MainComponent from './components/MainComponent.vue';
import FormComponent from './components/FormComponent.vue';
import "@fontsource/oswald";
import "@fontsource/oswald/500.css";
import "@fontsource/open-sans";




export default {
  name: 'App',
  components: {
    HeaderComponent,
    FooterComponent,
    MainComponent,
    FormComponent
}
}
</script>

<style lang="scss">
@import './style/mainStyle';
@import './style/_variables';
</style>
