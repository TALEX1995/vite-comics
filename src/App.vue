<script>
import '@fontsource-variable/open-sans';
import AppHeader from './components/AppHeader.vue'
export default {
  data() {
    return {

    }
  },

  components: {
    AppHeader
  }
}
</script>

<template>
  <AppHeader />
</template>


<style>
body {
  font-family: 'Open Sans Variable', sans-serif;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
}

img {
  max-width: 100%;
}

ul {
  list-style-type: none;
}
</style>
