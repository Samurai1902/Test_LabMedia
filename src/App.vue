<template>
    <HeaderMenu/>
    <h1 class="Opportunities-title">Еще больше возможностей</h1>
    <NewDesign/>
    <VideoInfo/>
    <Accessories/>
    <Services/>
</template>

<script setup>
import NewDesign from './components/NewDesign.vue';
import HeaderMenu from './components/menu.vue'
import VideoInfo from './components/video.vue'
import Accessories from './components/accessories.vue'
import Services from './components/services.vue'

</script>

<style>

.Opportunities-title{
    background-color: #ffffff;
    width: 950px;
    height: 50px;
    font-family: PT Root UI;
    font-size: 38px;
    font-weight: 700;
    line-height: 50px;
    text-align: left;
    margin: 40px 25px;
}

@media (max-width: 720px) {
    .Opportunities-title{
        width: 670px;
    }
}
</style>
