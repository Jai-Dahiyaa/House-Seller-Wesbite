<template>
    <footer class="footer">
        <div class="footer-line-div">
            <footerData />
            <Bottomline />
        </div>
    </footer>
</template>

<script setup>
import footerData from './footerData.vue';
import Bottomline from './Bottomline.vue';
</script>

<style scoped>
.footer {
    height: 40vh;
    width: 100%;
    padding: 1rem 1rem 0rem 1rem;
}

.footer-line-div {
    height: 100%;
    width: 100%;
    border-top: 2px solid #E3E3E3;
    padding-top: 2rem;
}
</style>