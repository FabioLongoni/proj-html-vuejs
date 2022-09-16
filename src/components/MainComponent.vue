<template>
  <div>
    <SloganSection/>
    <SpecialsPizzeSection/>
    <JumbotronSection/>
  </div>
  
</template>

<script>
import SloganSection from './SloganSection.vue';
import SpecialsPizzeSection from './SpecialsPizzeSection.vue';
import JumbotronSection from './JumbotronSection.vue';

export default {
  components: { SloganSection, SpecialsPizzeSection, JumbotronSection}
}
</script>

<style scoped lang="scss">
  
</style>