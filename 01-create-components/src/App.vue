<script setup>
import MainNavigation from './components/MainNavigation.vue';
</script>

<template>
    <header>
        <MainNavigation />
    </header>
</template>

<style scoped>
</style>


<style scoped>
    nav {
        background-color: #333;
        color: #fff;
        padding: 1rem;
    }

    ul {
        list-style: none;
        display: flex;
        gap: 1rem;
    }

    li {
        margin: 0;
    }

    a {
        color: #fff;
        text-decoration: none;
    }
    
</style>
