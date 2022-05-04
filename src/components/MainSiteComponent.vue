<template>
    <main>
        <SiteJumbotronSection />
        <SiteComicsSection />
        <SiteMainNavigator />
    </main>
    
</template>

<script>
import SiteComicsSection from "@/components/ComicsSectionComponent.vue"
import SiteMainNavigator from "@/components/NavigatorComponent.vue"
import SiteJumbotronSection from "@/components/JumbotronComponent.vue"
export default {
    name: 'SiteMain',
    components: {
        SiteComicsSection,
        SiteMainNavigator,
        SiteJumbotronSection
    }
}
</script>