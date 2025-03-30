<template>
    <div id="column2">
        <div id="img-div">
            <div id="bottom-img">
                <div id="bottom-div-1">
                    <IconCircleArrowRight id="icon" size="30px" stroke={2} />
                    <h1>Dream Home</h1>
                </div>
                <div id="bottom-div-2">
                    <p>
                        Find the perfect place to live, invest,<br/>
or sell with ease. Your real estate<br/> journey starts here!
                    </p>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
import { IconCircleArrowRight } from '@tabler/icons-vue';
</script>

<style scoped>
#column2 {
    height: 100%;
    width: 52%;
    display: flex;
    justify-content: center;
    align-items: center;
}

#img-div {
    height: 98%;
    width: 98%;
    background-color: darksalmon;
    border-radius: 0.5rem;
    display: flex;
    justify-content: end;
    align-items: end;
    background-image: url("../../../assets/section1/high.jpg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    border: none;
}

img {
    width: 100%;
    height: auto;
    image-rendering: "high-quality";
}

#bottom-img {
    height: 20%;
    width: 30%;
    background-image: url("../../../assets/backgrundSVG/VectorBottom3.png");
    position: relative;
    background-position: bottom;
    background-repeat: no-repeat;
    background-size: contain;
    left: 0.5rem;
    top: 0.3rem;
    z-index: 1;
}

#bottom-div-1 {
    height: 30%;
    width: 100%;
    display: flex;
}

#icon {
    margin-top: 2.5rem;
    margin-left: 1rem;
    color: #6582AD;
    rotate: 320deg;
}

#bottom-div-1 h1 {
    margin-top: 2.4rem;
    margin-left: 0.5rem;
    font-weight: 500;
}

#bottom-div-2 {
    height: 70%;
    width: 100%;
    display: flex;
    justify-content: start;
    align-items: center;
}

#bottom-div-2 p {
    margin-top: 1rem;
    font-size: 0.7rem;
    margin-left: 3.5rem;
}
</style>