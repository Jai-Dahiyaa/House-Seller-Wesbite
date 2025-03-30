<template>
    <div class="Column3-div">
        <div class="col3-div1">
            <div id="info-div">
                <h1>Who We Are</h1>
            </div>
        </div>
        <div class="col3-div2">
            <div id="div-2nd">
                <h1>Why Choose Us</h1>
            </div>
        </div>
    </div>
</template>

<script setup></script>

<style scoped>
.Column3-div {
    height: 100%;
    width: 100%;
    border-radius: 1rem;
    display: grid;
    grid-template-columns: repeat(1, 1fr);
    grid-template-rows: repeat(2, 1fr);
    gap: 1.5rem 0rem;
}

.col3-div1 {
    height: 100%;
    width: 100%;
    background-color: khaki;
    border-radius: 1rem;
    border: 1px solid #6582AD;
    background-image: url("../../assets/section4/img2.jpg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    padding: 1rem;
    display: flex;
    justify-content: start;
    align-items: end;
    color: white;
}

#info-div {
    height: 5rem;
    width: 20rem;
    background-color: #6582ad8a;
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 1rem;
}

#info-div h1 {
    font-size: 2.2rem;
    font-weight: 400;
}

.col3-div2 {
    height: 100%;
    width: 100%;
    background-color: khaki;
    border-radius: 1rem;
    border: 1px solid #6582AD;
    background-image: url("../../assets/section4/img3.jpg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    padding: 1rem;
    display: flex;
    justify-content: start;
    align-items: end;
    color: white;
}

#div-2nd {
    height: 5rem;
    width: 23rem;
    background-color: #6582ad8a;
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 1rem;
}

#div-2nd h1 {
    font-size: 2.2rem;
    font-weight: 400;
}
</style>