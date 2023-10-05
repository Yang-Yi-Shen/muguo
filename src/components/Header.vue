<script setup>
import { RouterLink } from 'vue-router';
</script>

<template>
    <header>
        <RouterLink to="/" class="logo-wrapper">
            <h2 class="heading logo">Muguo</h2>
        </RouterLink>
        <ul class="header-nav">
            <li class="header-nav-item">
                <RouterLink class="header-nav-link" to="/about">
                    <p class="header-nav-text">關於</p>
                </RouterLink>
            </li>
            <li class="header-nav-item">
                <RouterLink class="header-nav-link" to="/products">
                    <p class="header-nav-text">產品</p>
                </RouterLink>
            </li>
            <li class="header-nav-item">
                <RouterLink class="header-nav-link" to="/contact">
                    <p class="header-nav-text">聯絡</p>
                </RouterLink>
            </li>
        </ul>
    </header>
</template>

<style scoped>
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0px 150px;
}

.logo-wrapper {
    text-decoration: none;
}

.header-nav {
    list-style: none;
    padding-inline-start: 0px;
    display: flex;
    gap: 30px;
}

.header-nav-link {
    text-decoration: none;
    color: var(--text);
}

.header-nav-link:hover {
    color: var(--contrast);
}

/* nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.header-nav {
    list-style: none;
    padding-inline-start: 0px;
    display: flex;
    gap: 30px;
}

.header-nav-link {
    text-decoration: none;
    color: var(--text);
}

.header-nav-link:hover {
    color: var(--contrast);
} */
</style>