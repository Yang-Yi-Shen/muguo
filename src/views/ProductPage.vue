<script setup>
import { useRouter, RouterLink } from "vue-router";

import Header from '../components/Header.vue';
import Footer from '../components/Footer.vue';

const router = useRouter()
const itemName = router.currentRoute.value.params.name
const itemList = [
    {
        name_ch: "綜合禮盒",
        image: "cake_collection.jpeg",
        description: "有各種不同的甜點，是中秋節的理想禮物",
        price: 680,
        link: "collection"
    },
    {
        name_ch: "蛋黃酥",
        image: "egg_yolk_cake.jpeg",
        description: "大小官員出郭迎接，隨即差人報知龍虎山上清宮住持道眾，準備接詔。" ,
        price: 600,
        link: "eggyolk"
    },
    {
        name_ch: "菠蘿蛋黃酥",
        image: "carrot_egg_yolk_cake.jpeg",
        description: "次日，眾位官同送太尉到於龍虎山下。",
        price: 650,
        link: "carrot"
    },
    {
        name_ch: "綜合芋頭酥",
        image: "taro_cake.jpeg",
        description: "且說大尉洪信資擎御書，一行人從上了路途，不止一日，來到江西信州。",
        price: 550,
        link: "taro"
    },
    {
        name_ch: "鳳梨酥、蔓越莓酥1",
        image: "pineapple_cake.jpeg",
        description: "太尉看那官殿時，端的是好座上清宮。",
        price: 450,
        link: "pineapple"
    },
    {
        name_ch: "經典酥餅",
        image: "flatcakes.png",
        description: "青松屈曲，翠柏陰森。門懸敕額金書，戶列靈符玉篆",
        price: 390,
        link: "flatcakes"
    }
]

const currentItem = itemList.filter(item => item.link == itemName)[0]
console.log(currentItem)
</script>

<template>
    <Header />
    <main>
        <RouterLink :to="`/products/${currentItem.link}`" class="item-image-wrapper">
            <img class="item-image" :src="`/src/assets/${currentItem.image}`">
        </RouterLink>
        <div class="item-text">
            <RouterLink :to="`/products/${currentItem.link}`" class="item-name-wrapper" >
                <h1 class="item-name heading">{{ currentItem.name_ch }}</h1>
            </RouterLink>
            <p class="item-description">{{ currentItem.description }}</p>
            <p class="item-price heading">NT$ {{ currentItem.price }}</p>
        </div>
    </main>
    <Footer id="contact" />
</template>

<style scoped>
main {
    background-color: white;
    display: flex;
    gap: 50px;
    padding: 50px 200px;
}

.item-image-wrapper {
    width: 40%;
}

.item-image {
    width: 100%;
}

.item-name-wrapper {
    text-decoration: none;
}
</style>