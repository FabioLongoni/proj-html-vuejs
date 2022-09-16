<template>
  <div>
    <SloganSection/>
    <SpecialsPizzeSection/>
    <JumbotronSection/>
    <TeamAndPartnerSection />
    <MenuSection />
  </div>
  
</template>

<script>
import SloganSection from './SloganSection.vue';
import SpecialsPizzeSection from './SpecialsPizzeSection.vue';
import JumbotronSection from './JumbotronSection.vue';
import TeamAndPartnerSection from './TeamAndPartnerSection.vue';
import MenuSection from './MenuSection.vue';

export default {
  components: { SloganSection,
    SpecialsPizzeSection,
    JumbotronSection,
    TeamAndPartnerSection,
    MenuSection 
  }
}
</script>

<style scoped lang="scss">
  
</style>