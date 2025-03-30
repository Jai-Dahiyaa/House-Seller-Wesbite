<template>
    <div class="sec6-item-div">
        <div class="item-div">
            <IconCircleArrowRight stroke={2} class="icon"/>
            <button class="full-view-btn">
                <a href="#">
                    Click full View
                </a>
            </button>
        </div>
        <div class="item-div img2"></div>
        <div class="item-div img3"></div>
        <div class="item-div img4"></div>
        <div class="item-div img5"></div>
        <div class="item-div img6"></div>
        <div class="item-div img7"></div>
        <div class="item-div img8"></div>
        <div class="item-div img9"></div>
        <div class="item-div img0"></div>

    </div>
</template>

<script setup>
import { IconCircleArrowRight } from '@tabler/icons-vue';
</script>

<style scoped>
.sec6-item-div {
    height: 75%;
    width: 100%;
    padding: 2rem 8rem;
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    grid-template-rows: repeat(2, 1fr);
    gap: 1.5rem 3rem;
}

.item-div {
    height: 100%;
    width: 100%;
    background-color: lightcyan;
    border: 1px solid #6582AD;
    border-radius: 1rem;
    background-image: url("../../assets/section6/img1.jpg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    display: flex;
    align-items: end;
    padding: 0.6rem;
    gap: 0.5rem;
}

.icon {
    color: #6582AD;
    width: 2rem;
    height: 2rem;
}

.full-view-btn {
    height: 2rem;
    width: 8rem;
    border-radius: 50rem;
    background-color: white;
    border: none;
}

.full-view-btn a {
    font-family: "Orbitron";
    font-size: 0.7rem;
    color: #6582AD;
    text-decoration: none;
    font-weight: 500;
}

.img2 {
    background-image: url("../../assets/section6/img2.jpg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

.img3 {
    background-image: url("../../assets/section6/img3.jpg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

.img4 {
    background-image: url("../../assets/section6/img4.jpg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

.img5 {
    background-image: url("../../assets/section6/img5.jpg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

.img6 {
    background-image: url("../../assets/section6/img6.jpg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

.img7 {
    background-image: url("../../assets/section6/img7.jpg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

.img8 {
    background-image: url("../../assets/section6/img8.jpg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

.img9 {
    background-image: url("../../assets/section6/img9.jpg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}

.img0 {
    background-image: url("../../assets/section6/img10.avif");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}
</style>