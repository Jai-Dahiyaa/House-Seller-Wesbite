<template>
    <div class="logo-div">
        <div class="footerData-div">
            <div class="footer-logo"></div>
        </div>
        <div class="footerData-div data-div2">
            <ul>
                <li><h1 class="head">About Us</h1></li>
                <li><h1 class="first1">Mission</h1></li>
                <li><h1 class="second2">Vision</h1></li>
                <li><h1 class="third3">Career</h1></li>
                <li><h1 class="fourth4">Security</h1></li>
            </ul>
        </div>
        <div class="footerData-div data-div2">
            <ul>
                <li><h1 class="head">Resource</h1></li>
                <li><h1 class="first1">Blog</h1></li>
                <li><h1 class="second2">Press</h1></li>
                <li><h1 class="third3">Customers</h1></li>
            </ul>
        </div>
        <div class="footerData-div data-div2">
            <ul>
                <li><h1 class="head">Company</h1></li>
                <li><h1 class="first1">Consulting</h1></li>
                <li><h1 class="second2">Buying</h1></li>
                <li><h1 class="third3">Selling</h1></li>
            </ul>
        </div>
        <div class="footerData-div data-div2">
            <ul>
                <li><h1 class="head">Category</h1></li>
                <li><h1 class="first1">Modern Duplex House</h1></li>
                <li><h1 class="second2">Cabin House</h1></li>
                <li><h1 class="third3">Cattage New House</h1></li>
                <li><h1 class="fourth4">Rambler House</h1></li>
            </ul>
        </div>
    </div>
</template>

<script setup></script>

<style scoped>
.logo-div {
    height: 100%;
    width: 100%;
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    grid-template-rows: repeat(1, 1fr);
    gap: 2rem;
}

.footerData-div {
    height: 100%;
    width: 100%;
}

.footer-logo {
    height: 18%;
    width: 78%;
    background-image: url("../../assets/logo/logo-3-1.webp");
    background-position: center;
    background-repeat: no-repeat;
    background-size: contain;
}

.data-div2 ul {
    list-style: none;
    display: flex;
    flex-direction: column;
    margin-top: 0.5rem;
    gap: 2rem;
}

.data-div2 ul li:hover {
    cursor: pointer;
}

.head {
    font-size: 1.5rem;
    font-weight: 500;
}

.first1 {
    font-size: 1.5rem;
    font-weight: 400;
}

.second2 {
    font-size: 1.5rem;
    font-weight: 400;
}

.third3 {
    font-size: 1.5rem;
    font-weight: 400;
}

.fourth4 {
    font-size: 1.5rem;
    font-weight: 400;
}
</style>