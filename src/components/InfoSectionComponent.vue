<template>
    <section class="dc_info">
      <div class="container">
        <div class="row">
          <div class="col-2">
            <div class="info">
              <div class="row">
                <div class="col-3">
                  <div class="row column">
                    <div class="col-2-column">
                      <h3>DC COMICS</h3>
                      <ul>
                        <li>
                          <a href="">Characters</a>
                        </li>
                        <li>
                          <a href="">Comics</a>
                        </li>
                        <li>
                          <a href="">Movies</a>
                        </li>
                        <li>
                          <a href="">TV</a>
                        </li>
                        <li>
                          <a href="">Games</a>
                        </li>
                        <li>
                          <a href="">Videos</a>
                        </li>
                        <li>
                          <a href="">News</a>
                        </li>
                      </ul>
                    </div>
                    <!-- /.col-2 -->
                    <div class="col-2-column">
                      <h3>SHOP</h3>
                      <ul>
                        <li>
                          <a href="">Characters</a>
                        </li>
                        <li>
                          <a href="">Comics</a>
                        </li>
                      </ul>
                    </div>
                    <!-- /.col-2 -->
                  </div>
                  <!-- /.row -->
                 
                </div>
                <!-- /.col-3 -->
                <div class="col-3">
                  <h3>DC COMICS</h3>
                      <ul>
                        <li>
                          <a href="">Characters</a>
                        </li>
                        <li>
                          <a href="">Comics</a>
                        </li>
                        <li>
                          <a href="">Movies</a>
                        </li>
                        <li>
                          <a href="">TV</a>
                        </li>
                        <li>
                          <a href="">Games</a>
                        </li>
                        <li>
                          <a href="">Videos</a>
                        </li>
                        <li>
                          <a href="">News</a>
                        </li>
                        <li>
                          <a href="">News</a>
                        </li>
                        <li>
                          <a href="">News</a>
                        </li>
                        <li>
                          <a href="">News</a>
                        </li>
                        <li>
                          <a href="">News</a>
                        </li>
                      </ul>
                </div>
                <!-- /.col-3 -->
                <div class="col-3">
                  <h3>DC COMICS</h3>
                      <ul>
                        <li>
                          <a href="">Characters</a>
                        </li>
                        <li>
                          <a href="">Comics</a>
                        </li>
                        <li>
                          <a href="">Movies</a>
                        </li>
                        <li>
                          <a href="">TV</a>
                        </li>
                        <li>
                          <a href="">Games</a>
                        </li>
                      </ul>
                </div>
                <!-- /.col-3 -->
              </div>
              <!-- /.row -->

            </div>
          </div>
          <!-- /.col-2 -->
          <div class="col-2">
            <img src="@/assets/img/dc-logo-bg.png" alt="">
          </div>
          <!-- /.col-2 -->
        </div>
        <!-- /.row -->
      </div>
      <!-- /.container -->

    </section>
    <!-- /.dc_info -->
    
</template>

<script>
export default {
    name: 'FooterInfoSection'
}
</script>

<style lang="scss" scoped>
.dc_info {
  background-image: url('@/assets/img/footer-bg.jpg');
  height: 400px;
  background-size: cover;
  .col-3 {
      text-align: start;
  }
  h3 {
    color: white;
    font-weight: bold;
    margin-bottom: 1.2rem;
  }
  a {
    color: lightgray;
  }
  .row {
    column-gap: 3rem;
      .col-2:first-child {
        padding-top: 3rem;
      }
  }
  .row .column {
    flex-direction: column;
    row-gap: 1rem;
    
      .col-2-column {
        height: calc(100% / 2);
      }
  }
}
</style>


