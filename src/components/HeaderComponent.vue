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
            <li>
              <a href="">
                Character
              </a>
            </li>
            <li>
              <a href="" class="active">
                Comics
              </a>
            </li>
            <li>
              <a href="">
                Movies
              </a>
            </li>
            <li>
              <a href="">
                Tv
              </a>
            </li>
            <li>
              <a href="">
                Games
              </a>
            </li>
            <li>
              <a href="">
                Collecctibles
              </a>
            </li>
            <li>
              <a href="">
                Video
              </a>
            </li>
            <li>
              <a href="">
                Fans
              </a>
            </li>
            <li>
              <a href="">
                News
              </a>
            </li>
            <li>
              <a href="">
                Shops
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
    name: 'SiteHeader'
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
   
 

