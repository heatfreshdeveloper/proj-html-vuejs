<template>
  <div id="app">
    <contact-header-band></contact-header-band>
    <Header></Header>
    <Newsletter></Newsletter>
    <Footer></Footer>
    <Copyright-footer-band></Copyright-footer-band>
  </div>
</template>

<script>
import ContactHeaderBand from './components/ContactHeaderBand.vue'
import CopyrightFooterBand from './components/CopyrightFooterBand.vue'
import Footer from './components/Footer.vue'
import Header from './components/Header.vue'
import Newsletter from './components/Newsletter.vue'

export default {
  name: 'App',
  components: {
    ContactHeaderBand,
    Header,
    CopyrightFooterBand,
    Newsletter,
    Footer,

  }
}
</script>

<style lang="scss">
@import "@/styles/app.scss";
</style>
