<template>
    <section class="section8">
        <Column1 />
        <Column2 />
    </section>
</template>

<script setup>
import Column1 from './Sec8Col1.vue';
import Column2 from './Sec8Col2.vue';
</script>

<style scoped>
.section8 {
    height: 60vh;
    width: 100%;
    padding: 2.5rem;
    display: flex;
    flex-direction: row;
}
</style>