<template>
    <footer>
        <FooterInfoSection />
        <div class="sign_up">

        </div>
        <!-- /.sign_up -->
    </footer>
</template>

<script>
import FooterInfoSection from './InfoSectionComponent.vue'
export default {
    name: 'SiteFooter',
    components: {
        FooterInfoSection,
    }

}
</script>

<style lang="scss" scoped>
    // Section DC Info


.sign_up {
    height: 200px;
    background-color: black;
}
</style>