<template>
    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Properties</a></li>
            <li><a href="#">Abouts Us</a></li>
            <li><a href="#">Service</a></li>
            <li><a href="#">Blog/News</a></li>
            <li><a href="#">Contact Us</a></li>
        </ul>
    </nav>
</template>

<script setup></script>

<style scoped>
nav {
    height: 100%;
    width: 45%;
    display: flex;
    justify-content: start;
    align-items: center;
    padding-left: 0.8rem;
}

ul {
    display: flex;
    gap: 2.8rem;
    list-style: none;
    margin-top: 0.5rem;
}

li a {
    text-decoration: none;
    color: black;
    font-size: 1.1rem;
    font-weight: 400;
}

li a:hover {
    font-weight: 500;
    text-decoration: underline;
}
</style>