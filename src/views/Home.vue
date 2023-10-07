<script setup>
import { RouterLink } from 'vue-router';

import Footer from '../components/Footer.vue';
</script>

<template>
    <header>
        <nav class="header-top">
            <h2 class="heading logo">Muguo</h2>
            <ul class="header-nav">
                <li class="header-nav-item">
                    <RouterLink class="header-nav-link" to="/about"><p class="header-nav-text">關於</p></RouterLink>
                </li>
                <li class="header-nav-item">
                    <RouterLink class="header-nav-link" to="/products"><p class="header-nav-text">產品</p></RouterLink>
                </li>
                <li class="header-nav-item">
                    <a class="header-nav-link" href="#contacts"><p class="header-nav-text">聯絡</p></a>
                </li>
            </ul>
        </nav>
        <div class="header-bottom">
            <img class="header-image" src="/src/assets/cake_collection.jpeg">
            <div class="header-bottom-content">
                <h1 class="heading header-bottom-title">用愛心做的點心</h1>
                <p class="header-bottom-text">因幫了一個生鐵王員外兒子使錢</p>
            </div>
        </div>
    </header>
    <div id="products">
        <div class="products-container">
            <h1 class="products-heading heading">廚師退件 ✨</h1>
            <ul class="product-list">
                <li class="product-list-item">
                    <img class="product-image" src="/src/assets/egg_yolk_cake.jpeg">
                    <a class="product-link" href="/"><h2 class="product-name heading">紅豆月餅</h2></a>
                    <p class="product-description">一個很香的，用紅豆做的月餅。豆子都是廚師自手收集的。</p>
                    <p class="heading">NT$ 500</p>
                </li>
                <li class="product-list-item">
                    <img class="product-image" src="/src/assets/taro_cake.jpeg">
                    <a class="product-link" href="/"><h2 class="product-name heading">紅豆月餅</h2></a>
                    <p class="product-description">一個很香的，用紅豆做的月餅。豆子都是廚師自手收集的。</p>
                    <p class="heading">NT$ 500</p>
                </li>
                <li class="product-list-item">
                    <img class="product-image" src="/src/assets/pineapple_cake.jpeg">
                    <a class="product-link" href="/"><h2 class="product-name heading">紅豆月餅</h2></a>
                    <p class="product-description">一個很香的，用紅豆做的月餅。豆子都是廚師自手收集的。</p>
                    <p class="heading">NT$ 500</p>
                </li>
            </ul>
            <RouterLink to="/products" class="products-btn-container" target="_blank">
                <button class="products-btn">跟多選擇 >></button>
            </RouterLink>
        </div>
    </div>
    <div id="reviews">
        <h1 class="review-title heading">客戶評價</h1>
        <ul class="reviews-list">
            <li class="review-item">
                <h2 class="review-author heading">沈洋逸</h2>
                <p class="review-text">這些月餅很好吃！我對產品完全滿意</p>
                <p class="review-rating">⭐⭐⭐⭐⭐</p>
            </li>
            <li class="review-item">
                <h2 class="review-author heading">沈洋逸</h2>
                <p class="review-text">這些月餅很好吃！我對產品完全滿意</p>
                <p class="review-rating">⭐⭐⭐⭐⭐</p>
            </li>
            <li class="review-item">
                <h2 class="review-author heading">沈洋逸</h2>
                <p class="review-text">這些月餅很好吃！我對產品完全滿意</p>
                <p class="review-rating">⭐⭐⭐⭐⭐</p>
            </li>
            <li class="review-item">
                <h2 class="review-author heading">沈洋逸</h2>
                <p class="review-text">這些月餅很好吃！我對產品完全滿意</p>
                <p class="review-rating">⭐⭐⭐⭐⭐</p>
            </li>
            <li class="review-item">
                <h2 class="review-author heading">沈洋逸</h2>
                <p class="review-text">這些月餅很好吃！我對產品完全滿意</p>
                <p class="review-rating">⭐⭐⭐⭐⭐</p>
            </li>
        </ul>
    </div>
    <div id="about">
        <div class="about-content">
            <h1 class="about-title heading">關於我們</h1>
            <p class="about-text">孫子曰：凡用兵之法，馳車千駟，革車千乘，帶甲十萬，千里饋糧，則內外之費
                ，賓客之用，膠漆之材，車甲之奉，日費千金，然后十萬之師舉矣。
            </p>
            <RouterLink class="about-btn-container" to="/about" target="_blank">
                <button class="about-btn">了解更多 >></button>
            </RouterLink>
        </div>
        <img class="about-image" src="/src/assets/logo.jpeg">
    </div>
    <div id="about-mobile">
        <h1 class="about-title-mobile heading">關於我們</h1>
        <img class="about-image-mobile" src="/src/assets/logo.jpeg">
        <p class="about-text-mobile">孫子曰：凡用兵之法，馳車千駟，革車千乘，帶甲十萬，千里饋糧，則內外之費
            ，賓客之用，膠漆之材，車甲之奉，日費千金，然后十萬之師舉矣。
        </p>
        <RouterLink class="about-btn-container" to="/about" target="_blank">
            <button class="about-btn">了解更多 >></button>
        </RouterLink>    
    </div>
    <Footer id="contacts" />
</template>

<style scoped>
header {
    padding: 0px 200px;
}

.logo:hover {
    color: var(--contrast);
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
    font-size: 18px;
}

.header-nav-link {
    text-decoration: none;
    color: var(--text);
}

.header-nav-link:hover {
    color: var(--contrast);
}

.header-bottom {
    display: flex;
    justify-content: center;
    gap: 50px;
    padding: 50px 0px;
}

.header-image {
    width: min(400px, 50%);
    object-fit: scale-down;
    flex-basis: 1;
}

.header-bottom-content {
    flex-basis: 1;
}

.header-bottom-title {
    font-size: 48px;
}

.header-bottom-text {
    font-size: 24px;
}

/* products section */
#products {
    background-color: white;
    padding: 50px 0px;
    display: flex;
    justify-content: center;
}

.products-container {
    padding: 0px 200px;
}

.product-list {
    list-style: none;
    padding-inline-start: 0px;
    display: flex;
    gap: 50px;
}

.product-list-item {
    min-width: 230px;
}

.product-image {
    width: 100%;
    transition: scale 0.4s, margin-bottom 0.4s;
}

.product-image:hover {
    scale: 1.05;
    margin-bottom: 5px;
}

.product-link {
    text-decoration: none;
}

.product-name:hover {
    color: var(--contrast);
}

.products-btn-container {
    display: flex;
    text-decoration: none;
}

.products-btn {
    background-color: white;
    border: 2px solid var(--contrast);
    border-radius: 5px;
    color: var(--contrast);
    font-size: 16px;
    padding: 5px 15px;
    text-align: center;
    margin: 0px auto;
    transition: background-color 0.4s, color 0.4s, border 0.4s;
}

.products-btn:hover {
    background-color: var(--headings);
    color: white;
    border: 2px solid var(--headings)
}

/* reviews section */
#reviews {
    padding: 50px 0px;
}

.review-title {
    padding: 0px 150px;
}

.reviews-list {
    list-style: none;
    padding-inline-start: 0px;
    padding: 0px 50px;
    display: flex;
    gap: 20px;
    overflow-x: scroll;
    transition: scale 0.4s;
}

.reviews-list:hover {
    scale: 1.02;
}

.review-item {
    min-width: 280px;
    background-color: white;
    border-radius: 5px;
    padding: 10px 30px;
}

/* about section */
#about {
    max-width: 100vw;
    display: flex;
    background-color: white;
    padding: 100px 250px;
    gap: 100px;
    justify-content: center;
}

#about-mobile {
    display: none;
}

.about-content {
    min-width: 160px;
}

.about-title {
    margin: 0px;
}

.about-image {
    width: 300px;
    object-fit: scale-down;
}

.about-btn-container {
    text-decoration: none;
}

.about-btn {
    background-color: white;
    border: 2px solid var(--contrast);
    border-radius: 5px;
    color: var(--contrast);
    font-size: 16px;
    padding: 5px 15px;
    text-align: center;
    margin: 0px auto;
    transition: background-color 0.4s, color 0.4s, border 0.4s;
}

.about-btn:hover {
    background-color: var(--headings);
    color: white;
    border: 2px solid var(--headings)
}

/* contactss section */
#contacts {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 50px 0px;
}

.contacts-subtitle {
    font-weight: 500;
    font-family: 'Noto Serif TC';
    margin: 0px 0px 30px;
}

.contacts-list {
    list-style: none;
    padding-inline-start: 0px;
    display: flex;
    gap: 30px;
    align-items: center;
    justify-content: center;
}

.contacts-item-icon {
    font-size: 30px;
    display: flex;
    flex-direction: column;
    align-items: center;
    background-color: white;
    color: var(--text);
    padding: 10px;
    border-radius: 50%;
}

.contacts-item-icon:hover {
    color: #3e4e50c5
}

@media (max-width: 768px) {
    header {
        padding: 0px;
    }

    .header-top {
        padding: 0px 50px;
    }

    .header-bottom {
        padding: 0px 0px 30px;
        display: block;
        text-align: center;
    }

    .header-image {
        width: 100%;
    }

    .header-bottom-content {
        padding: 20px;
    }

    /* products section */
    #products {
        padding: 50px 0px;
    }

    .products-container {
        padding: 0px 50px;
    }

    .products-heading {
        padding: 20px 0px;
        margin: 0px;
    }

    .product-list {
        flex-direction: column;

    }
    .product-list-item {
        max-width: 100vw;
    }

    .product-image {
        border: 0.1px solid var(--text);
    }

    /* reviews section */
    #reviews {
        padding: 20px 0px 50px;
    }

    .review-title {
        padding: 0px 20px;
    }

    .reviews-list {
        padding: 0px 20px;
    }

    /* about */
    #about {
        display: none;
    }

    #about-mobile {
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 20px 50px 50px;
        background-color: white;
    }
    
    .about-title {
        margin: auto;
    }

    .about-image-mobile {
        width: 100%;
    }

    .about-text-mobile {
        margin: 30px 0px;
    }
}
</style>