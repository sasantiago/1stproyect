<template>
<h1 class="p-70 f-100 d-middle ">Hola mundo en Vue Js</h1>
<section class="banner-section w-100 p-10">
    <form action="">
        <div class="search-input d-middle">
            <input type="text">
            <span>Search Movie</span>
        </div>
    </form>
    <div class="container-image-banner">
        <img src="" alt="">
    </div>
</section>
<div class="container-image-banner">
    <img src="imageUrl" alt="">
</div>

</template>

<script  lang="ts" setup>
import { ref } from 'vue';
import image from "@/assets/images/header-img.svg"
const imageUrl = ref(image)

</script>

<style scoped lang="scss">
.banner-section{
    height: 50hv;
    background-image: url(../assets/);
    background-size: cover;
    display: flex;
    justify-content: space-around;
}

</style>