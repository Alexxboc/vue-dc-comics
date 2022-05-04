<template>
    <div class="card">
        <div class="img_container">
            <img :src="img" alt="">
        </div>
        <!-- /.img_container -->
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
.img_container {
    height: 200px;
    img {
    aspect-ratio: 1 / 1;
    max-height: 100%;
    object-fit: cover;
    object-position: top;
    }
}

.title {
    color: white;
    font-weight: 600;
    font-size: 13px;
    text-transform: uppercase;
    text-align: start;
    padding: 1rem 0;
}
</style>
