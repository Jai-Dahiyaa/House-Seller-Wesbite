<template>
    <div id="header-section1-div">
        <HeaderMain/>
        <Section1Main/>
    </div>
</template>

<script setup>
import HeaderMain from "./header/HeaderMain.vue";
import Section1Main from "./section1/Section1Main.vue";
</script>

<style scoped>
#header-section1-div {
    width: 100%;
    height: 51rem;
    background-image: url("../../assets/backgrundSVG/VectorImg.png");
    background-position: bottom;
    background-repeat: no-repeat;
    background-size: contain;
}
</style>