<template>
    <div class="sec6-menu-div">
        <div class="menu-div">
            <ul>
                <li><a href="#">Trending Properties</a></li>
                <li><a href="#">Most Viewed</a></li>
                <li><a href="#">Popular Picks</a></li>
                <li><a href="#">Top Choices</a></li>
                <li><a href="#">Top Rated Homes</a></li>
            </ul>
        </div>
    </div>
</template>

<script setup></script>

<style scoped>
.sec6-menu-div {
    height: 5%;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
}

.menu-div {
    height: 100%;
    width: 60%;
    background-color: #B5CADB;
    border-radius: 0.5rem;
    display: flex;
    justify-content: center;
    align-items: center;
}

.menu-div ul {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 6rem;
    list-style: none;
}

.menu-div ul li a {
    text-decoration: none;
    color: black;
}

.menu-div ul li a:hover {
    font-weight: 500;
    border-bottom: 1px solid black;
    padding-bottom: 0.2rem;
}
</style>