<script setup>
  import Products from './components/Products.vue';
  import Header from './components/Header.vue';

  const products = [
    {
      id: 1,
      image: 'https://hi-stores.ru/upload/iblock/bb9/bb92417353b89cd736ee7af0b04ea86f.jpg',
      title: 'Apple iPhone 14 Pro Max',
      description: '128GB Deep Purple',
      price: 900
    },
    {
      id: 2,
      image: 'https://hi-stores.ru/upload/iblock/669/s5ocnqx2go7ixc3f5mk36w5rphgfykgm.jpg',
      title: 'Iphone 12',
      description: 'this is iphone',
      price: 20000
    },
    {
      id: 3,
      image: 'https://dicentre.ru/wa-data/public/shop/products/14/59/25914/images/38409/38409.970.jpg',
      title: 'Iphone 13',
      description: 'this is iphone',
      price: 20000
    },
    {
      id: 4,
      image: 'https://iphoriya.ru/wp-content/uploads/iphone-14-purple.jpg',
      title: 'Apple iPhone 14 Pro',
      description: '512GB Gold (MQ233)',
      price: 20000
    },
    {
      id: 5,
      image: 'https://appdom.ru/image/cache/catalog/iphone/ip15/apple-iphone-15-pink-1x-1000x1000.jpg',
      title: 'Iphone 15',
      description: 'this is iphone',
      price: 20000
    },
    {
      id: 6,
      image: 'https://hi-stores.ru/upload/iblock/bb9/bb92417353b89cd736ee7af0b04ea86f.jpg',
      title: 'Apple iPhone 14 Pro Max',
      description: '128GB Deep Purple',
      price: 900
    },
    {
      id: 7,
      image: 'https://hi-stores.ru/upload/iblock/669/s5ocnqx2go7ixc3f5mk36w5rphgfykgm.jpg',
      title: 'Iphone 12',
      description: 'this is iphone',
      price: 20000
    },
    {
      id: 8,
      image: 'https://dicentre.ru/wa-data/public/shop/products/14/59/25914/images/38409/38409.970.jpg',
      title: 'Iphone 13',
      description: 'this is iphone',
      price: 20000
    },
    {
      id: 9,
      image: 'https://iphoriya.ru/wp-content/uploads/iphone-14-purple.jpg',
      title: 'Apple iPhone 14 Pro',
      description: '512GB Gold (MQ233)',
      price: 20000
    },
    {
      id: 10,
      image: 'https://appdom.ru/image/cache/catalog/iphone/ip15/apple-iphone-15-pink-1x-1000x1000.jpg',
      title: 'Iphone 15',
      description: 'this is iphone',
      price: 20000
    },
    {
      id: 6,
      image: 'https://hi-stores.ru/upload/iblock/bb9/bb92417353b89cd736ee7af0b04ea86f.jpg',
      title: 'Apple iPhone 14 Pro Max',
      description: '128GB Deep Purple',
      price: 900
    },
    {
      id: 7,
      image: 'https://hi-stores.ru/upload/iblock/669/s5ocnqx2go7ixc3f5mk36w5rphgfykgm.jpg',
      title: 'Iphone 12',
      description: 'this is iphone',
      price: 20000
    },
    {
      id: 8,
      image: 'https://dicentre.ru/wa-data/public/shop/products/14/59/25914/images/38409/38409.970.jpg',
      title: 'Iphone 13',
      description: 'this is iphone',
      price: 20000
    },
    {
      id: 9,
      image: 'https://iphoriya.ru/wp-content/uploads/iphone-14-purple.jpg',
      title: 'Apple iPhone 14 Pro',
      description: '512GB Gold (MQ233)',
      price: 20000
    },
    {
      id: 10,
      image: 'https://appdom.ru/image/cache/catalog/iphone/ip15/apple-iphone-15-pink-1x-1000x1000.jpg',
      title: 'Iphone 15',
      description: 'this is iphone',
      price: 20000
    }
  ]
</script>

<template>
  <Header></Header>
  <br>
  <Products :products="products"/>
</template>

<style scoped>
   @import url('https://fonts.googleapis.com/css2?family=Manrope:wght@200..800&display=swap');
   
   *{
    font-family: 'Manrope';
   }
</style>
