<template>
  <div class="home">
    <HeaderAlan />
    <HeroAlan />
    <WomanAlan />
    <InstaAlan />
    <PartnerAlan />
    <FooterAlan />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderAlan from '@/components/HeaderAlan.vue';
import HeroAlan from '@/components/HeroAlan.vue';
import WomanAlan from '@/components/WomanAlan.vue';
import InstaAlan from '@/components/InstaAlan.vue';
import PartnerAlan from '@/components/PartnerAlan.vue';
import FooterAlan from '@/components/FooterAlan.vue';


export default {
  name: 'HomeView',
  components: {
    HeaderAlan,
    HeroAlan,
    WomanAlan,
    InstaAlan,
    PartnerAlan,
    FooterAlan
  }
}
</script>
