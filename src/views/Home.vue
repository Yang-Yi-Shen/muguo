<script setup></script>

<template>
    <header>
        <nav class="header-top">
            <h2 class="heading logo">新華麵包店</h2>
            <ul class="header-nav">
                <li class="header-nav-item">
                    <a class="header-nav-link" href="/"><p class="header-nav-text">關於</p></a>
                </li>
                <li class="header-nav-item">
                    <a class="header-nav-link" href="/"><p class="header-nav-text">產品</p></a>
                </li>
                <li class="header-nav-item">
                    <a class="header-nav-link" href="/"><p class="header-nav-text">過程</p></a>
                </li>
                <li class="header-nav-item">
                    <a class="header-nav-link" href="/"><p class="header-nav-text">聯絡</p></a>
                </li>
            </ul>
        </nav>
        <div class="header-bottom">
            <img class="header-image" src="/src/assets/mooncake_packaging.png">
            <div class="header-bottom-content">
                <h1 class="heading header-bottom-title">用愛心做的點心</h1>
                <p class="header-bottom-text">新華面包店是一個很小的店。我們只能做少量產品，但是從這裡發出的每一個蛋糕會從滿愛心跟高級的材料。</p>
            </div>
        </div>
    </header>
</template>

<style scoped>
header {
    padding: 0px 50px;
}

nav {
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

.header-bottom {
    display: flex;
    gap: 50px;
    padding: 50px 0px;
}

.header-image {
    height: 400px;
}
</style>