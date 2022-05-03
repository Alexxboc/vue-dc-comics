<template>
    <footer>
        <FooterInfoSection />
        <FooterSignUp />
    </footer>
</template>

<script>
import FooterInfoSection from './InfoSectionComponent.vue';
import FooterSignUp from './SignUpComponent.vue'
export default {
    name: 'SiteFooter',
    components: {
        FooterInfoSection,
        FooterSignUp
    }

}
</script>

<style lang="scss" scoped>

</style>
            