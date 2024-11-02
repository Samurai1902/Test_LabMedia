<template>
    <section class="design">
        <hr class="design-line">
        <h2 class="design-title">Новый дизайн</h2>
        <div class="design-cards">
            <div class="card">
                <img src="@/assets/img/buy-now_banner_galaxy-s10.jpg" alt="" class="card-img"/>
                <p class="card-text">Абсолютно новый Infinity-O экран — на передней стороне смартфона нет ничего, кроме огромного экрана и фронтальной камеры.</p>
            </div>
            <div class="card" id="card_white">
                <img src="@/assets/img/Group 13 2.jpg" alt="" class="card-img"/>
                <p class="card-text">Для любителей роскоши, модель S10+ будет выпускаться в керамическом корпусе черного и белого цветов.</p>
            </div>
            <div class="card" id="card_white">
                <img src="@/assets/img/colours_s10.jpg" alt="" class="card-img"/>
                <p class="card-text">Смартфоны доступны в 4х стильных цветах: Перламутр, Аквамарин, Оникс и Цитрус(для S10e).</p>
            </div>
            <div class="card" id="card_white">
                <img src="@/assets/img/gorilla_glass.jpg" alt="" class="card-img"/>
                <p class="card-text">В моделях S10 и S10+ установлены защитные стекла нового поколения – Gorilla Glass 6.</p>
            </div>
        </div>
        
    </section>
</template>

<script>

</script>

<style>
@font-face {
    font-family: PT Root UI;
    src: url('@/assets/fonts/PT-Root-UI_Regular.ttf');
}

.design {
    width: 950px;
    height: 481px;
    margin: 40px 25px 60px 25px;
}

.design-line {
    width: 950px;
    height: 1px;
    opacity: 0.3;
    margin: 0;
}

.design-title {
    width: 950px;
    height: 40px;
    font-family: PT Root UI;
    margin: 40px 0px 54px 0px;
}

.design-cards {
    display: flex;
    flex-direction: row;
}

#card_white {
    background-color: transparent;
    padding: 0;
    margin-left: 20px;
}

#card_white .card-text{
    color: #171717;
}

.card {
    max-width: 222px;
    height: max-content;
    border-radius: 5px;
    background-color: #171717;
    display: flex;
    flex-direction: column;
    padding: 20px 15px;
    align-items: center;
    gap: 20px;
}

.card-img {
    max-width: 220px;
    
}

.card-text {
    color: #ffffff;
    font-family: PT Root UI;
    font-size: 14px;
    font-weight: 500;
    line-height: 21px;
    text-align: left;
    margin: 0;
}

</style>
  