<template>
    <section id="section-1">
        <Column1/>
        <Column2/>
    </section>
</template>

<script setup>
import Column1 from './Column1.vue';
import Column2 from './Column2.vue';
</script>

<style scoped>
#section-1 {
    height: 85%;
    width: 100%;
    display: flex;
}
</style>