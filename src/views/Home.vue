<template>
  <div class="home">
    <HeaderSaputra /> 
    <AwalSaputra />
    <ListSaputra />
    <InstaSaputra />
    <PartnerSaputra />
    <FooterSaputra />
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'
import HeaderSaputra from '@/components/HeaderSaputra.vue'
import AwalSaputra from '@/components/AwalSaputra.vue'
import ListSaputra from '@/components/ListSaputra.vue'
import InstaSaputra from '@/components/InstaSaputra.vue'
import PartnerSaputra from '@/components/PartnerSaputra.vue'
import FooterSaputra from '@/components/FooterSaputra.vue'


export default {
  name: 'Home',
  components: {
    HeaderSaputra,
    AwalSaputra,
    ListSaputra,
    InstaSaputra,
    PartnerSaputra,
    FooterSaputra
  }
}
</script>
