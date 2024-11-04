<template>
    <section class="accessories">
        <h2 class="accessories-title">Аксессуары</h2>
        <div class="accessories-cards">
            <div class="card">
                <img src="@/assets/img/galaxy-s10_accessories_cases.jpg" alt="" class="card-img"/>
                <hr class="card-line-down">
                <p class="card-text">Для любителей роскоши, модель S10+ будет выпускаться в керамическом корпусе черного и белого цветов.</p>
            </div>
            <div class="card">
                <img src="@/assets/img/galaxy-s10_accessories_power.jpg" alt="" class="card-img"/>
                <hr class="card-line-down">
                <p class="card-text">Для любителей роскоши, модель S10+ будет выпускаться в керамическом корпусе черного и белого цветов.</p>
            </div>
            <div class="card">
                <hr class="card-line-up">
                <p class="card-text">Galaxy S10+ в режиме Dex поддерживает широкоформатные мониторы. Мощный смартфон превращается в мощный десктоп.</p>
            </div>
            <div class="card">
                <hr class="card-line-up">
                <p class="card-text">Смартфон S10 сразу укомплектован защитной пленкой.</p>
            </div>
        </div>
        
    </section>
</template>

<script>

</script>

<style scoped>
@font-face {
    font-family: PT Root UI;
    src: url('@/assets/fonts/PT-Root-UI_Regular.ttf');
}

.accessories {
    height: max-content;
    width: 950px;
    margin: 40px 25px 61px 25px;
}
.accessories-title {
    width: 950px;
    height: 40px;
    font-family: PT Root UI;
    margin: 40px 0px 54px 0px;
    font-size: 30px;
    line-height: 40px;
    text-align: left;
}
.accessories-cards {
    display: flex;
    flex-direction: row;
    gap: 20px;
}
.card {
    max-width: 222px;
    height: max-content;
    border-radius: 5px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    gap: 20px;
    background-color: transparent;
}
.card-img {
    max-width: 222px;
}
.card-text {
    color: #000000;
    font-family: PT Root UI;
    font-size: 16px;
    font-weight: 500;
    line-height: 24px;
    text-align: left;
    margin: 0;
    width: 223px;
}
.card-line-down{
    width: 222px;
    height: 1px;
    opacity: 0.1;
    color: #000000;
    margin: 0;
}
.card-line-up{
    width: 50px;
    height: 1px;
    color: #000000;
    margin: 0;
}

@media (max-width: 720px) {
    .accessories{
        width: 670px;
        margin: 0px 25px 61px 25px;
    }
    .accessories-title{
        width: 670px;
        font-size: 30px;
        line-height: 40px;
    }
    .accessories-cards{
        flex-wrap: wrap;
        gap: 50px 20px;
    }
    .card{
        max-height: 319px;
        max-width: 325px;
    }
    .card-text{
        width: 325px;
        font-size: 14px;
        line-height: 21px;
    }
    .card-line-down{
        width: 325px;
    }
    .card-img {
        max-width: 325px;
        width: 325px;
    }
}
</style>
  