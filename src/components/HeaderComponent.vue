<template>
    <header>
      <div class="container">
        <div class="navbar">
           <div class="logo">
          <img width="80" src="@/assets/img/dc-logo.png" alt="">
        </div>
        <!-- /.logo -->
        <div class="header_menu">
          <ul>
            <li v-for="(titolo, index) in menu" :key="index">
              <a href="">
                {{titolo}}
              </a>
            </li>
          </ul>
        </div>
        <!-- /.header_menu -->
        </div>
        <!-- /.navbar -->
      </div>
      <!-- /.container -->
    </header>
</template>

<script>

export default {
    name: 'SiteHeader',
    data() {
      return {
        menu: [
        'characters',
        'comics',
        'movies',
        'tv',
        'games',
        'collectibles',
        'video',
        'fans',
        'news',
        'shops'
      ]
      }
      
    }
}
</script>


<style lang="scss" scoped>
    /* Header */
header {
  .navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .header_menu {
    ul {
      display: flex;
         li {
       a {
    display: inline-block;
    padding: 3rem 1rem;
    color: $dc-text-dark;
    text-transform: uppercase;
    font-weight: 600;
    font-size: 14px;
    border-bottom: 3px solid transparent;
    &:hover {
      border-bottom: 3px solid $dc-primary;
      color: $dc-primary;
    }
      }
    }
  }
    .active {
    border-bottom: 3px solid $dc-primary;
    color: $dc-primary;
    }
  }
  
  
}
</style>
   
 

