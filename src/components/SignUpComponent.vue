<template>
    <div class="sign_up">
            <div class="container">
                <div class="row">
                    <div class="col-2">
                        <div class="btn">
                            <a href="">sign-up now!</a>
                        </div>
                        <!-- /.btn -->
                    </div>
                    <!-- /.col-2 -->
                    <div class="col-2">
                        <div class="follow_title">
                            <h3>Follow us</h3>
                            <div class="follow_links">
                            <img src="@/assets/img/footer-facebook.png" alt="">
                            <img src="@/assets/img/footer-twitter.png" alt="">
                            <img src="@/assets/img/footer-youtube.png" alt="">
                            <img src="@/assets/img/footer-periscope.png" alt="">
                            <img src="@/assets/img/footer-pinterest.png" alt="">
                        </div>
                        <!-- /.follow_links -->
                        </div>
                        <!-- /.follow_title -->
                    </div>
                    <!-- /.col-2 -->
                </div>
                <!-- /.row -->
             </div>
                <!-- /.container -->
        </div>
        <!-- /.sign_up -->
</template>

<script>
export default {
    name: 'FooterSignUp'
}
</script>

<style lang="scss" scoped>
.sign_up {
    height: 200px;
    background-color: $dc-footer-bg;
    position: relative;
    z-index: 1;
    .container {
        height: 100%;
    }
    .row {
        height: 100%;
    }
    .col-2 {
        display: flex;
        align-items: center;
    }
    .col-2:last-child {
        justify-content: end;
    }
}
                    

.btn {
    a {
    color: $dc-text-white;
    text-transform: uppercase;
    font-size: 20px;
    font-weight: 500;
    border: 2px solid $dc-primary;
    padding: 0.5rem 1rem;
    }
}

.follow_title {
    display: flex;
    column-gap: 2rem;
    align-items: center;
    justify-content: end;
    h3 {
    text-transform: uppercase;
    font-size: 20px;
    color: $dc-primary;
    font-weight: 900;
    }
    img {
        padding-left: 1rem;
    }
}
</style>