<script setup>
const { product } = defineProps(["product"]);
</script>

<template>
    <div class="product" :data-id="product.id">
        <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="#909090" stroke-width="1" stroke-linecap="round" stroke-linejoin="round" class="icon icon-tabler icons-tabler-outline icon-tabler-heart"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M19.5 12.572l-7.5 7.428l-7.5 -7.428a5 5 0 1 1 7.5 -6.566a5 5 0 1 1 7.5 6.572" /></svg>
        <img :src="product.image" alt="photo">
        <p>{{ product.title }} {{ product.description }}</p>
        <h2>${{ product.price }}</h2>
        <button>Buy Now</button>
    </div>
</template>

<style scoped>
*{
    padding: 0;
    margin: 0;
}
    .product{
        width: 268px;
        height: 432px;
        background-color: #F6F6F6;
        border-radius: 9px;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        gap: 16px;
    }
    .product svg{
        position: relative;
        left: 100px;
    }
    .product img{
        width: 160px;
        height: 160px;
    }
    .product p{
        text-align: center;
        margin: 0 15px;
        height: 35px;
    }
    .product button{
        padding: 12px 64px;
        background-color: black;
        color: white;
        border-radius: 8px;
    }
</style>