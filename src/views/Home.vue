<script setup>
import { RouterLink } from 'vue-router';
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
                    <a class="header-nav-link" href="/"><p class="header-nav-text">產品</p></a>
                </li>
                <li class="header-nav-item">
                    <a class="header-nav-link" href="/"><p class="header-nav-text">聯絡</p></a>
                </li>
            </ul>
        </nav>
        <div class="header-bottom">
            <img class="header-image" src="/src/assets/cake_collection.jpeg">
            <div class="header-bottom-content">
                <h1 class="heading header-bottom-title">用愛心做的點心</h1>
                <p class="header-bottom-text">孫子曰：兵者，國之大事，死生之地，存亡之道，不可不察也。
                    故經之以五，校之以計，而索其情：一曰道，二曰天，三曰地，四曰將，五曰法
                    。道者，令民于上同意者也，可與之死，可與之生，民不詭也。天者，陰陽、寒
                    暑、時制也。地者，高下、遠近、險易、廣狹、死生也。將者，智、信、仁、勇
                    、嚴也。法者，曲制、官道、主用也。凡此五者，將莫不聞，知之者勝，不知之
                    者不勝。故校之以計，而索其情。曰：主孰有道？將孰有能？天地孰得？法令孰
                    行？兵眾孰強？士卒孰練？賞罰孰明？吾以此知勝負矣。</p>
            </div>
        </div>
    </header>
    <div id="products">
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
        <div class="products-btn-container">
            <button class="products-btn">跟多選擇 >></button>
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
                ，賓客之用，膠漆之材，車甲之奉，日費千金，然后十萬之師舉矣。其用戰也貴
                勝，久則鈍兵挫銳，攻城則力屈，久暴師則國用不足。夫鈍兵挫銳，屈力殫貨，
                則諸侯乘其弊而起，雖有智者，不能善其后矣。故兵聞拙速，未睹巧之久也。夫
                兵久而國利者，未之有也。故不盡知用兵之害者，則不能盡知用兵之利也。</p>
            <button class="about-btn">學習更多 >></button>
        </div>
        <img class="about-image" src="/src/assets/logo.jpeg">
    </div>
    <div id="contacts">
        <h1 class="contacts-title heading">跟我們聯絡</h1>
        <h2 class="contacts-subtitle">下訂單跟探險我們的內容</h2>
        <ul class="contacts-list">
            <li class="contacts-item">
                <a class="contacts-item-link">
                    <i class="contacts-item-icon fa-brands fa-line"></i>  
                </a>
            </li>
            <li class="contacts-item">
                <a class="contacts-item-link">
                    <i class="contacts-item-icon fa-brands fa-facebook"></i>  
                </a>
            </li>
            <li class="contacts-item">
                <a class="contacts-item-link">
                    <i class="contacts-item-icon fa-brands fa-instagram"></i>  
                </a>
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

.header-nav-link:hover {
    color: var(--contrast);
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
    padding: 50px 200px;
}

.product-list {
    list-style: none;
    padding-inline-start: 0px;
    display: flex;
    gap: 50px;
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
    display: flex;
    background-color: white;
    padding: 100px 250px;
    gap: 100px;
}

.about-image {
    width: 300px;
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
</style>