<template>
    <div id="login-register-div">
        <button>
            <a href="#">Login/Register</a>
        </button>
    </div>
</template>

<script setup></script>

<style scoped>
#login-register-div {
    height: 100%;
    width: 11%;
    display: flex;
    justify-content: center;
    align-items: center;
}

button {
    height: 42%;
    width: 90%;
    background-color: #6582AD;
    border: none;
    border-radius: 0.3rem;
}

button a{
    text-decoration: none;
    color: white;
    font-size: 1.1rem;
    font-weight: 400;
    font-family: "Orbitron";
}
</style>