<template>
    <div class="column1-main-div">
        <h1>Top Properties</h1>
        <p>Explore top-tier properties in prime<br/>
            locations with unmatched value.<br/>
            From luxurious villas to budget-<br/>
            friendly homes, find the perfect<br/>
            place that suits your lifestyle and<br/>
            needs!"</p>
            <button>
                <a href="#">
                    Explore Now
                </a>
            </button>
    </div>
</template>

<script setup></script>

<style scoped>
.column1-main-div {
    height: 100%;
    width: 21%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: start;
    gap: 1.5rem;
}

.column1-main-div h1 {
    font-size: 2rem;
    font-weight: 500;
}

.column1-main-div p {
    font-size: 1.2rem;
}

.column1-main-div button {
    width: 12rem;
    height: 3rem;
    border: 2px solid #58709D;
    border-radius: 0.5rem;
    background-color: white;
}

.column1-main-div button a {
    text-decoration: none;
    color: #58709D;
    font-family: "Orbitron";
    font-size: 1.3rem;
}
</style>