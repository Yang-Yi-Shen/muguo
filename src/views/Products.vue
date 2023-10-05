<script setup>
import Header from '../components/Header.vue';
import Footer from '../components/Footer.vue';
</script>

<template>
    <Header />
    <main>
        <div class="product">
            <img class="product-image" src="/src/assets/cake_collection.jpeg">
            <a class="product-link" href="/">
                <h2 class="product-name heading">紅豆月餅</h2>
            </a>
            <p class="product-description">一個很香的，用紅豆做的月餅。豆子都是廚師自手收集的。</p>
            <p class="product-price heading">NT$ 500</p>
        </div>
        <div class="product">
            <img class="product-image" src="/src/assets/egg_yolk_cake.jpeg">
            <a class="product-link" href="/">
                <h2 class="product-name heading">紅豆月餅</h2>
            </a>
            <p class="product-description">一個很香的，用紅豆做的月餅。豆子都是廚師自手收集的。</p>
            <p class="product-price heading">NT$ 500</p>
        </div>
        <div class="product">
            <img class="product-image" src="/src/assets/carrot_egg_yolk_cake.jpeg">
            <a class="product-link" href="/">
                <h2 class="product-name heading">紅豆月餅</h2>
            </a>
            <p class="product-description">一個很香的，用紅豆做的月餅。豆子都是廚師自手收集的。</p>
            <p class="product-price heading">NT$ 500</p>
        </div>
        <div class="product">
            <img class="product-image" src="/src/assets/taro_cake.jpeg">
            <a class="product-link" href="/">
                <h2 class="product-name heading">紅豆月餅</h2>
            </a>
            <p class="product-description">一個很香的，用紅豆做的月餅。豆子都是廚師自手收集的。</p>
            <p class="product-price heading">NT$ 500</p>
        </div>
        <div class="product">
            <img class="product-image" src="/src/assets/pineapple_cake.jpeg">
            <a class="product-link" href="/">
                <h2 class="product-name heading">紅豆月餅</h2>
            </a>
            <p class="product-description">一個很香的，用紅豆做的月餅。豆子都是廚師自手收集的。</p>
            <p class="product-price heading">NT$ 500</p>
        </div>
        <div class="product">
            <img class="product-image" src="/src/assets/flatcakes.png">
            <a class="product-link" href="/">
                <h2 class="product-name heading">紅豆月餅</h2>
            </a>
            <p class="product-description">一個很香的，用紅豆做的月餅。豆子都是廚師自手收集的。</p>
            <p class="product-price heading">NT$ 500</p>
        </div>
    </main>
    <Footer />
</template>

<style scoped>
main {
    background-color: white;
    padding: 100px 200px;
    display: flex;
    flex-flow: wrap;
    justify-content: space-between;
    gap: max(50px, auto);
    row-gap: 70px;
}

.product {
    width: min(30%, 300px);
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
</style>