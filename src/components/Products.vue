<script setup>
import Product from './Product.vue';
const { products } = defineProps(["products"]);
</script>

<template>
    <div class="products">
        <Product v-for="product in products" :key="product.id" :product="product" />
    </div>
</template>

<style scoped>
    .products{
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        justify-content: center;
        gap: 20px;
    }
</style>