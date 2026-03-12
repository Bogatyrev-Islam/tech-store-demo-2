<script setup>

</script>

<template>
    <header>
        <nav>
            <h2>cyber</h2>
            <div class="search">
             <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="#989898" stroke-width="1" stroke-linecap="round" stroke-linejoin="round" class="icon icon-tabler icons-tabler-outline icon-tabler-search"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M3 10a7 7 0 1 0 14 0a7 7 0 1 0 -14 0" /><path d="M21 21l-6 -6" /></svg>
             <input type="text" placeholder="Search">
            </div>
            <nav>
                <a href="">Home</a>
                <a href="">About</a>
                <a href="">Contact Us</a>
                <a href="">Blog</a>
            </nav>
            <section>
                <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1" stroke-linecap="round" stroke-linejoin="round" class="icon icon-tabler icons-tabler-outline icon-tabler-heart"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M19.5 12.572l-7.5 7.428l-7.5 -7.428a5 5 0 1 1 7.5 -6.566a5 5 0 1 1 7.5 6.572" /></svg>
                <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1" stroke-linecap="round" stroke-linejoin="round" class="icon icon-tabler icons-tabler-outline icon-tabler-shopping-cart"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M4 19a2 2 0 1 0 4 0a2 2 0 1 0 -4 0" /><path d="M15 19a2 2 0 1 0 4 0a2 2 0 1 0 -4 0" /><path d="M17 17h-11v-14h-2" /><path d="M6 5l14 1l-1 7h-13" /></svg>
                <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1" stroke-linecap="round" stroke-linejoin="round" class="icon icon-tabler icons-tabler-outline icon-tabler-user"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M8 7a4 4 0 1 0 8 0a4 4 0 0 0 -8 0" /><path d="M6 21v-2a4 4 0 0 1 4 -4h4a4 4 0 0 1 4 4v2" /></svg>
            </section>
        </nav>
        <section class="banner">
            <div class="banner-content">
            <h2>Pro.Beyond.</h2>
            <span>IPhone 14 <b>Pro</b></span>
            <p>Created to change everything for the better. For everyone</p>
            <button>Shop Now</button>
        </div>
            <img src="../../public/Banner.jpg" alt="">
        </section>
    </header>
</template>

<style scoped>
header nav{
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    gap: 16px;
}
header .search{
    width: 372px;
    background-color: #F5F5F5;
    border-radius: 10px;
    padding: 16px;
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 5px;
}
header input {
    background-color: #F5F5F5;
    border: none;
}
header nav{
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 52px;
}
header nav a{
    font-weight: 600;
    color: black;
    text-decoration: none;
}
header section{
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 24px;
}
header .banner {
    width: 100%;
}
header .banner-content{
    color: white;
    position: absolute;
    left: 200px;
}
header .banner h2{
    margin: 0;
    opacity: 50%;
}
header .banner span{
    font-weight: 100;
    margin: 0;
    font-size: 90px;  
}
header .banner span b{
    font-weight: 900; 
}
header .banner p{
    margin: 0;
    margin-bottom: 20px;
    opacity: 50%;
}
header .banner img{
    width: 100%;
}
header .banner button{
        padding: 16px 56px;
        font-size: 16px;
        background: none;
        border: 1px solid white;
        color: white;
        border-radius: 8px;
}
</style>