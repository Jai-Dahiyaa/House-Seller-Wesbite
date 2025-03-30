<template>
    <section class="section5">
        <div class="sec5-main-div">
            <Column1 />
            <Column2 />
        </div>
    </section>
</template>

<script setup>
import Column1 from './Column1.vue';
import Column2 from './Column2.vue';
</script>

<style scoped>
.section5 {
    height: 50vh;
    width: 103%;
    background-image: url("../../assets/section5/vectorSec5.png");
    background-position: right;
    background-repeat: no-repeat;
    background-size: contain;
    margin-top: 2rem;
    padding: 2rem 1rem;
}

.sec5-main-div {
    height: 100%;
    width: 100%;
    display: flex;
}
</style>