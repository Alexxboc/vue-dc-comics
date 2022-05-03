<template>
    <main>
        <SiteHeroImage />
        <SiteMainNavigator />
    </main>
    
</template>

<script>
import SiteHeroImage from "@/components/HeroComponent.vue"
import SiteMainNavigator from "@/components/NavigatorComponent.vue"
export default {
    name: 'SiteMain',
    components: {
        SiteHeroImage,
        SiteMainNavigator,
    }
}
</script>