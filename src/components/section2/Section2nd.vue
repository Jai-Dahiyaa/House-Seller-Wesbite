<template>
    <section class="section2">
        <Column1/>
        <Column2/>
    </section>
</template>

<script setup>
import Column1 from './Column1.vue';
import Column2 from './Column2.vue';
</script>

<style scoped>
.section2 {
    height: 90vh;
    width: 100%;
    /* background-color: antiquewhite; */
    display: flex;
    align-items: center;
    padding: 2rem 0px;
}
</style>