<template>
    <div class="Opportunities">
        <h1 class="Opportunities-title">Еще больше возможностей</h1>
        <NewDesign/>
    </div>
</template>

<script setup>
import NewDesign from './components/NewDesign.vue';

</script>

<style>
.Opportunities {
    width: 1000px;
    height: max-content;
    background-color: #ffffff;
}

.Opportunities-title{
    width: 950px;
    height: 50px;
    font-family: PT Root UI;
    font-size: 38px;
    font-weight: 700;
    line-height: 50px;
    text-align: left;
    margin: 40px 25px;
}
</style>
