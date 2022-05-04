<template>
    <div class="card">
              <img :src="img" alt="">
              <div class="title">
                <span>{{type}}</span>
              </div>
              <!-- /.title -->
            </div>
            <!-- /.card -->
</template>

<script>

export default {
    name: 'ComicsCard',
    props: {
        img: String,
        type: String
    }
}
</script>

<style lang="scss" scoped>
.card {
    position: relative;
    img{
      width: 240px;
    }
    .title {
      color: $dc-text-white;
      text-transform: uppercase;
      font-weight: 600;
      text-align: start;
      position: absolute;
      bottom:0;
      background-color: $dc-banner-bg;
      width: 100%;
      padding-bottom: 2rem 0;
      padding-bottom: 4rem;
      padding-top: 1rem;
    }
    
  }
</style>
