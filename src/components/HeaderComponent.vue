<template>
    <header>
      <div class="container">
        <div class="navbar">
           <div class="logo">
          <img src="@/assets/img/dc-logo.png" alt="">
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
        'character',
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
    padding: 2rem 0;
  }

  .header_menu {
    ul {
      display: flex;
         li {
    padding: 0 1rem;
       a {
    color: black;
    text-transform: uppercase;
    font-weight: 600;
    font-size: 14px;
      }
    }
  }
    .active {
    border-bottom: 3px solid blue;
    color: blue;
    }
  }
  
  
}
</style>
   
 

