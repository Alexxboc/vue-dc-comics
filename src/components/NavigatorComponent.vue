<template>
    <div class="navigator">
      <div class="container">
        <div class="row">
          <div class="col-5" v-for="card in cards" :key="card.id"  >
              <div class="card">
                   <div class="nav_img">
                        <img :src="card.src" alt="alt" :class="card.id === 4 ? 'w-30' : '' ">
                    </div>
                    <!-- /.nav_img -->
                    <div class="nav_title">
                        <h3>{{card.titolo}}</h3>
                    </div>
                    <!-- /.nav_title -->
              </div>
              <!-- /.card -->
           </div>
          <!-- /.col-5 -->

          

           
      </div>
      <!-- /.row -->
    </div>
    <!-- /.container -->
  </div>
    <!-- /.navigator -->
      
</template>

<script>
export default {
    name: 'SiteMainNavigator',
    data() {
        return {
            cards: [
                {
                    id: 1,
                    src: require('@/assets/img/buy-comics-digital-comics.png'),
                    titolo:'Digital Comics'
                },
                {
                    id: 2,
                    src: require('@/assets/img/buy-comics-merchandise.png'),
                    titolo:'DC Merchandise'
                },
                {
                    id: 3,
                    src: require('@/assets/img/buy-comics-subscriptions.png'),
                    titolo:'Subscription'
                },
                {
                    id: 4,
                    src: require('@/assets/img/buy-comics-shop-locator.png'),
                    titolo:'comic shop locator'
                },
                {
                    id: 5,
                    src: require('@/assets/img/buy-dc-power-visa.svg'),
                    titolo:'dc power visa'
                },
            
            
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
.navigator {
  background-color: $dc-primary;
  padding: 3rem 0;
  position: relative;
  z-index: 1;

  .col-5 {
      width: calc(100% / 5);
  }
  .card {
    display: flex;
    column-gap: 1rem;
    justify-content: center;
    align-items: center;
    color: $dc-text-white;
    text-transform: uppercase;
    img {
        width: 45px;
    }
  }
}
</style>

