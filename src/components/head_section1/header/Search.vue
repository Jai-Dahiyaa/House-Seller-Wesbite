<template>
    <div id="search-div">
        <IconSearch id="IconSearch" stroke={6} />
        <input placeholder="Search Property" type="text">
    </div>
</template>

<script setup>
import { IconSearch } from '@tabler/icons-vue';
</script>

<style scoped>
#search-div {
    height: 100%;
    width: 32%;
    display: flex;
    justify-content: end;
    align-items: center;
    padding-right: 1.1rem;
}

input {
    height: 42%;
    width: 79%;
    border: 1px solid #545454;
    padding-left: 1.3rem;
    border-radius: 50rem;
    font-family: "Orbitron";
}

input::placeholder {
    font-size: 1.1rem;
}

#IconSearch {
    color: #828282;
    position: relative;
    left: 27.2rem;
    height: 2rem;
    width: 2rem;
    stroke-width: 2;
    bottom: 0.1rem;
}
</style>