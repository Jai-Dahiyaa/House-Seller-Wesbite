<template>
    <div class="container">
        <HeadSection1 />
        <Section2 />
        <Section3 />
        <Section4 />
        <Section5 />
        <Section6 />
        <Section7 />
        <Section8 />
        <Footer />
    </div>
</template>

<script setup>
import HeadSection1 from "./components/head_section1/HeadSection1.vue";
import Section2 from "./components/section2/Section2nd.vue";
import Section3 from "./components/section3/MainSection3rd.vue";
import Section4 from "./components/section4/MainSection4.vue";
import Section5 from "./components/section5/MainSection5.vue";
import Section6 from "./components/section6/MainSection6.vue";
import Section7 from "./components/section7/Sec7Main.vue";
import Section8 from "./components/section8/MainSection8.vue";
import Footer from "./components/footer/MainFooter.vue"
</script>

<style scoped>
.container {
    display: flex;
    min-height: 100vh;
    flex-direction: column;
}
</style>