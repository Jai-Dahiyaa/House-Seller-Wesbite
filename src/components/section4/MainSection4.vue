<template>
    <section class="section4">
        <Column1/>
        <Column2/>
        <Column3/>
    </section>
</template>

<script setup>
import Column1 from './Sec4Column1.vue';
import Column2 from './Sec4Column2.vue';
import Column3 from './Sec4Column3.vue';
</script>

<style scoped>
.section4 {
    height: 100vh;
    width: 100%;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    padding: 2rem;
    gap: 1.5rem;
}
</style>