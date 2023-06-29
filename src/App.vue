<script>
import '@fontsource-variable/open-sans';
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooterTop from './components/AppFooterTop.vue'
import AppFooterBot from './components/AppFooterBot.vue'
export default {
  data() {
    return {

    }
  },

  components: {
    AppHeader,
    AppMain,
    AppFooterTop,
    AppFooterBot
  }
}
</script>

<template>
  <AppHeader />
  <AppMain />
  <AppFooterTop />
  <AppFooterBot />
</template>


<style lang="scss">
@use './assets/scss/style.scss'
</style>
