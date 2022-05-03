<template>
  <div id="app">
    <SiteHeader />
    <SiteMain />
    <SiteFooter />

    
    
    
  </div>
</template>

<script>
import SiteHeader from './components/HeaderComponent.vue';
import SiteMain from './components/MainSiteComponent.vue';
import SiteFooter from './components/FooterComponent.vue';

export default {
  name: 'App',
  components: {
    SiteHeader,
    SiteMain,
    SiteFooter,
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
  
}

a {
  text-decoration: none;
}



/* Utilities */
.container {
  max-width: 1440px;
  margin: auto;
}

.row {
  display: flex;
}

.col-2 {
  width: calc(100% / 2);
}

/* Main */

/* Footer */





</style>
