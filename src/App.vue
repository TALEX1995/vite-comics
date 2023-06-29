<script>
import '@fontsource-variable/open-sans';
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
export default {
  data() {
    return {

    }
  },

  components: {
    AppHeader,
    AppMain
  }
}
</script>

<template>
  <AppHeader />
  <AppMain />
</template>


<style>
/* Reset */
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

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

a {
  text-decoration: none;
}
</style>
