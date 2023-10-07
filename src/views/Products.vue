<script setup>
import Header from '../components/Header.vue';
import Footer from '../components/Footer.vue';
import Product from '../components/Product.vue';
</script>

<template>
    <Header />
    <main>
        <Product image="cake_collection.jpeg" name="綜合禮盒" description="有各種不同的甜點，是中秋節的理想禮物" price="680" />
        <Product image="egg_yolk_cake.jpeg" name="蛋黃酥" description="大小官員出郭迎接，隨即差人報知龍虎山上清宮住持道眾，準備接詔。" price="600" />
        <Product image="carrot_egg_yolk_cake.jpeg" name="菠蘿蛋黃酥" description="次日，眾位官同送太尉到於龍虎山下。" price="650" />
        <Product image="taro_cake.jpeg" name="綜合芋頭酥" description="且說大尉洪信資擎御書，一行人從上了路途，不止一日，來到江西信州。" price="550" />
        <Product image="pineapple_cake.jpeg" name="鳳梨酥、蔓越莓酥1" description="太尉看那官殿時，端的是好座上清宮。" price="450" />
        <Product image="flatcakes.png" name="經典酥餅" description="青松屈曲，翠柏陰森。門懸敕額金書，戶列靈符玉篆" price="390" />
    </main>
    <Footer id="contact" />
</template>

<style scoped>
main {
    background-color: white;
    padding: 100px min(200px, 15%);
    display: flex;
    flex-flow: wrap;
    justify-content: space-between;
    gap: max(50px, auto);
    row-gap: 70px;
}

.product-name:hover {
    color: var(--contrast);
}

@media (max-width: 768px) {
    main {
        padding: 20px;
        gap: 20px;
    }

    .product {
        width: calc((100vw - 60px) / 2);
    }
}
</style>