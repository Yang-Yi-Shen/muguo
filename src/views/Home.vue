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
    <div id="products">
        <h1 class="products-heading heading">廚師退件 ✨</h1>
        <ul class="product-list">
            <li class="product-list-item">
                <img class="product-image" src="/src/assets/fancy_mooncakes.png">
                <a class="product-link" href="/"><h2 class="product-name heading">紅豆月餅</h2></a>
                <p class="product-description">一個很香的，用紅豆做的月餅。豆子都是廚師自手收集的。</p>
                <p class="heading">NT$ 500</p>
            </li>
            <li class="product-list-item">
                <img class="product-image" src="/src/assets/fancy_mooncakes.png">
                <a class="product-link" href="/"><h2 class="product-name heading">紅豆月餅</h2></a>
                <p class="product-description">一個很香的，用紅豆做的月餅。豆子都是廚師自手收集的。</p>
                <p class="heading">NT$ 500</p>
            </li>
            <li class="product-list-item">
                <img class="product-image" src="/src/assets/fancy_mooncakes.png">
                <a class="product-link" href="/"><h2 class="product-name heading">紅豆月餅</h2></a>
                <p class="product-description">一個很香的，用紅豆做的月餅。豆子都是廚師自手收集的。</p>
                <p class="heading">NT$ 500</p>
            </li>
        </ul>
    </div>
</template>

<style scoped>
header {
    padding: 0px 150px;
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

/* products section */
#products {
    background-color: white;
    padding: 50px 150px;
}

.product-list {
    list-style: none;
    padding-inline-start: 0px;
    display: flex;
    gap: 20px;
}

.product-list-item {
    border: 1px solid black;
    padding: 20px;
}

.product-image {
    width: 100%;
}

.product-link {
    text-decoration: none;
}
</style>