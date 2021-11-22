<template>
  <div id="app">
    <contact-header-band></contact-header-band>
  </div>
</template>

<script>
import ContactHeaderBand from './components/ContactHeaderBand.vue'

export default {
  name: 'App',
  components: {
    ContactHeaderBand

  }
}
</script>

<style lang="scss">
@import "@/styles/app.scss";
</style>
