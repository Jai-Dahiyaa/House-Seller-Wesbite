<template>
    <div class="search-property-btn-div">
        <button>
            <IconSearch stroke={2} id="icon"/>
            <a href="#">
                Search
            </a>
        </button>
    </div>
</template>

<script setup>
import { IconSearch } from '@tabler/icons-vue';
</script>

<style scoped>
.search-property-btn-div {
    height: 15%;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}

.search-property-btn-div  button {
    height: 3.5rem;
    width: 13rem;
    border: none;
    color: white;
    background-color: #7696BB;
    border-radius: 50rem;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 0.5rem;
    font-family: "Orbitron";
}

.search-property-btn-div  button a {
    font-size: 1.5rem;
    font-weight: 400;
    text-decoration: none;
    color: white;
}

#icon {
    height: 1.8rem;
    width: 1.8rem;
}
</style>