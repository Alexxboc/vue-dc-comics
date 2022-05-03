<template>
    <section class="hero_image">
      <div class="container">
        <div class="content">
          <h2>Content Goes Here</h2>
        </div>
        <!-- /.content -->
      </div>
      <!-- /.container -->
    </section>
    <!-- /.hero_image -->
</template>

<script>
export default {
    name:'SiteHeroImage'
}
</script>

<style lang="scss" scoped>
.hero_image {
  background-color: rgb(33, 32, 32) ;
  color: white;
  font-size: 30px;
  padding: 3rem 0;
  .content {
    text-align: start;
    h2::before {
      content:'-->'
    }
    h2::after {
      content:'<--'
    }
  }
}
</style>
