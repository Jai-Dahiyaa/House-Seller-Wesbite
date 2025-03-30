<template>
    <section class="section7">
        <div class="find-property-div">
            <div class="back-img-data-div">
                <TopColumn/>
                <BottomData/>
                <SearchBtn/>
            </div>
        </div>
    </section>
</template>

<script setup>
import TopColumn from "./TopInfo.vue"
import BottomData from "./SelectData.vue"
import SearchBtn from "./SearchBtn.vue"
</script>

<style scoped>
.section7 {
    height: 60vh;
    width: 100%;
    margin-top: 4rem;
    display: flex;
    justify-content: center;
}

.find-property-div {
    height: 100%;
    width: 70%;
    background-color: #D3DFE9;
    border-radius: 1rem;
    padding: 2rem;
}

.back-img-data-div {
    height: 100%;
    width: 100%;
    background-image: url("../../assets/section7_8/img1.png");
    background-position: bottom;
    background-repeat: no-repeat;
    background-size: contain;
}
</style>