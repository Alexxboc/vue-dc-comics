<template>
  <div id="app">
    <SiteHeader />
    
    
  </div>
</template>

<script>
import SiteHeader from './components/HeaderComponent.vue'

export default {
  name: 'App',
  components: {
    SiteHeader,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

/* Common rules */

* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

img {
  max-width: 100%;
}

ul {
  list-style: none;
  display: flex;
}

a {
  text-decoration: none;
}



/* Utilities */
.container {
  max-width: 1440px;
  margin: auto;
}

/* Main */
// Section Hero Image

// Section Navigator

// Section DC Info

/* Footer */

</style>
