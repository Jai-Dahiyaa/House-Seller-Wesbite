<template>
    <div class="column1-div">
        <div class="img-div">
            <div class="section2-column1-info">
                <h1>
                    Explore Iconic Properties in <br/>Prime Locations!
                </h1>
                <p>
                    From modern skyscrapers to cozy homes, our<br/>
                    listings feature properties designed for comfort<br/>
                    and luxury. Explore top locations, stunning <br/>
                    architecture, and future-ready investments <br/>
                    today!
                </p>
                <button>
                    <a href="#">Schedule a Visit</a>
                </button>
            </div>
        </div>
    </div>
</template>

<script setup></script>

<style scoped>
.column1-div {
    height: 100%;
    width: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
}

.img-div {
    height: 98%;
    width: 98%;
    border: none;
    border-radius: 1.5rem;
    background-image: url("../../assets/section2/section2-1.webp");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    padding: 1rem;
    display: flex;
    justify-content: start;
    align-items: end;
}

.section2-column1-info {
    height: 35%;
    width: 50%;
    background-color: rgba(255, 255, 255, 0.589);
    border: 1px solid white;
    border-radius: 1.5rem;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: start;
    gap: 0.8rem;
    padding: 1rem;
}

.section2-column1-info h1 {
    font-size: 1.5rem;
    font-weight: 500;
}

.section2-column1-info p {
    font-size: 0.9rem;
}

.section2-column1-info button {
    height: 3rem;
    width: 10rem;
    background-color: white;
    color: black;
    border-radius: 50rem;
    border: none;
}

.section2-column1-info button a {
    text-decoration: none;
    font-size: 0.8rem;
    color: black;
    font-weight: 500;
    font-family: "Orbitron";
}
</style>