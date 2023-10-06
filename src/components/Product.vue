<script setup>
import { isIntegerKey } from '@vue/shared';

defineProps({
    image: String,
    name: String,
    description: String,
    price: Number
})
</script>

<template>
    <div class="product">
        <img class="product-image" :src="`/src/assets/${image}`">
        <h2 class="product-name heading">{{ name }}</h2>
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

.product-name:hover {
    color: var(--contrast);
}
</style>