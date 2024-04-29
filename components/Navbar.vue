<script setup lang="ts">

</script>

<template>
    <header class="header-container">
        <nav class="navbar container">
            <img class="logo" src="~/assets/images/logo-v1.png" alt="Initium Digital logo.">
            <ul>
            <li>
                <NuxtLink to="/">Home</NuxtLink>
            </li>
        </ul>
        </nav>
    </header>
</template>

<style scoped>
.header-container {
    width: 100%;
    background: var(--header-footer-color);

    .navbar {
        display: flex;
        padding: 1em 2em;
        justify-content: space-between;

        .logo {
            margin: .5rem;
        }

        ul, li {
            margin: 0;
            list-style: none;
            padding: 0;
        }
    }



    .navbar ul li a {
        color: black;
        text-decoration: none;
        margin: auto ;
    }
}
</style>