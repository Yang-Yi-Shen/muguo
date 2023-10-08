<script setup>
import { RouterLink } from "vue-router";
defineProps({
    image: String,
    name: String,
    description: String,
    price: String,
    link: String
})
</script>

<template>
    <div class="product">
        <RouterLink :to="`/products/${ link }`">
            <img class="product-image" :src="image">
        </RouterLink>
        <RouterLink :to="`/products/${ link }`" class="product-name-wrapper" >
            <h2 class="product-name heading">{{ name }}</h2>
        </RouterLink>
        <p class="product-description">{{ description }}</p>
        <p class="product-price heading">NT$ {{ price }}</p>
    </div>
</template>

<style scoped>
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

.product-name-wrapper {
    text-decoration: none;
}

.product-name:hover {
    color: var(--contrast);
}
</style>