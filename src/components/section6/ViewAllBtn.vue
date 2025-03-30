<template>
    <div class="viewbtn-div">
        <button>
            <a href="#">View All</a>
        </button>
    </div>
</template>

<script setup></script>

<style scoped>
.viewbtn-div {
    height: 8%;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}

.viewbtn-div button {
    height: 70%;
    width: 12rem;
    border: 2px solid #6582AD;
    border-radius: 0.5rem;
    background-color: white;
}

.viewbtn-div button a {
    font-family: "Orbitron";
    font-size: 1.8rem;
    color: #6582AD;
    text-decoration: none;
}
</style>