<template>
    <main>
        <SiteJumbotronSection />
        <SiteComicsSection />
        <SiteBanner />
    </main>
    
</template>

<script>
import SiteComicsSection from "@/components/ComicsSectionComponent.vue"
import SiteBanner from "@/components/BannerComponent.vue"
import SiteJumbotronSection from "@/components/JumbotronComponent.vue"
export default {
    name: 'SiteMain',
    components: {
        SiteComicsSection,
        SiteBanner,
        SiteJumbotronSection
    }
}
</script>