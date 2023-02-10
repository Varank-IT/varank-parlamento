<template>
    <div class="container">
        <Hero />
        <AboutSection />
        <AboutSection3></AboutSection3>
        <Day1Table />
        <FaqSection />
        <AboutSection2 />
        <MapSection />
        <TransportationSection />
    </div>
</template>

<script>
import Hero from '../components/Hero.vue';
import AboutSection from '../components/AboutSection.vue';
import AboutSection3 from '../components/AboutSection3.vue';
import Day1Table from '../components/Day1Table.vue';
import FaqSection from '../components/FaqSection.vue';
import AboutSection2 from '../components/AboutSection2.vue';
import MapSection from '../components/MapSection.vue'
import TransportationSection from '../components/TransportationSection.vue';


export default {
    name: 'MainView',
    components: {
        Hero,
        AboutSection,
        AboutSection3,
        Day1Table,
        FaqSection,
        AboutSection2,
        MapSection,
        TransportationSection,
    }
}
</script>

<style scoped>
.container {
    height: 100%;
    width: 100%;
}
</style>