<template>
  <div id="app">
    <contact-header-band></contact-header-band>
    <Header></Header>
  </div>
</template>

<script>
import ContactHeaderBand from './components/ContactHeaderBand.vue'
import Header from './components/Header.vue'

export default {
  name: 'App',
  components: {
    ContactHeaderBand,
    Header,

  }
}
</script>

<style lang="scss">
@import "@/styles/app.scss";
</style>
