<template>
    <header id="header">
        <Logo/>
        <Menu/>
        <Search/>
        <LoginRegister/>
    </header>
</template>

<script setup>
import Logo from "./Logo.vue"
import Menu from "./Menu.vue"
import Search from "./Search.vue"
import LoginRegister from "./LoginRegister.vue"
</script>

<style scoped>
#header {
    height: 7.5rem;
    width: 100%;
    /* background-color: bisque; */
    display: flex;
    justify-content: start;
    align-items: center;
}
</style>