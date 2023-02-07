<template>
    <div class="container">
        <Hero />
        <AboutSection />
        <Day1Table />
        <FaqSection />
        <AboutSection2 />
        <TransportationSection />
        <MapSection />
    </div>
</template>

<script>
import Hero from '../components/Hero.vue';
import AboutSection from '../components/AboutSection.vue';
import Day1Table from '../components/Day1Table.vue';
import FaqSection from '../components/FaqSection.vue';
import AboutSection2 from '../components/AboutSection2.vue';
import TransportationSection from '../components/TransportationSection.vue';
import MapSection from '../components/MapSection.vue';


export default {
    name: 'MainView',
    components: {
        Hero,
        AboutSection,
        Day1Table,
        FaqSection,
        AboutSection2,
        TransportationSection,
        MapSection
    }
}
</script>

<style scoped>
.container {
    height: 100%;
    width: 100%;
}
</style>