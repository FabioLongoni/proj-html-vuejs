<template>
  <div>
    <SloganSection/>
    <SpecialsPizzeSection/>
    <JumbotronSection/>
    <TeamAndPartnerSection />
  </div>
  
</template>

<script>
import SloganSection from './SloganSection.vue';
import SpecialsPizzeSection from './SpecialsPizzeSection.vue';
import JumbotronSection from './JumbotronSection.vue';
import TeamAndPartnerSection from './TeamAndPartnerSection.vue';

export default {
  components: { SloganSection, SpecialsPizzeSection, JumbotronSection, TeamAndPartnerSection }
}
</script>

<style scoped lang="scss">
  
</style>