<template>
    <section class="design">
        <hr class="design-line">
        <h2 class="design-title">Новый дизайн</h2>
        <div class="design-cards">
            <div class="card card1" id="card_black">
                <img src="@/assets/img/buy-now_banner_galaxy-s10.jpg" alt="" class="card-img"/>
                <hr>
                <p class="card-text">Абсолютно новый Infinity-O экран — на передней стороне смартфона нет ничего, кроме огромного экрана и фронтальной камеры.</p>
            </div>
            <div class="card card2" id="card_white">
                <img src="@/assets/img/Group 13 2.jpg" alt="" class="card-img"/>
                <hr id="line-s10">
                <p class="card-text">Для любителей роскоши, модель S10+ будет выпускаться в керамическом корпусе черного и белого цветов.</p>
            </div>
            <div class="card card3" id="card_white">
                <img src="@/assets/img/colours_s10.jpg" alt="" class="card-img"/>
                <p class="card-text">Смартфоны доступны в 4х стильных цветах: Перламутр, Аквамарин, Оникс и Цитрус(для S10e).</p>
            </div>
            <div class="card card4" id="card_white">
                <img src="@/assets/img/gorilla_glass.jpg" alt="" class="card-img"/>
                <p class="card-text">В моделях S10 и S10+ установлены защитные стекла нового поколения – Gorilla Glass 6.</p>
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

.design {
    width: 950px;
    height: max-content;
    margin: 40px 25px 60px 25px;
}
.design-line {
    height: 1px;
    opacity: 0.3;
    margin: 0;
}
.design-title {
    width: 950px;
    height: 40px;
    font-family: PT Root UI;
    margin: 40px 0px 54px 0px;
    font-size: 30px;
    line-height: 40px;
    text-align: left;
}
.design-cards {
    display: flex;
    flex-direction: row;
    gap: 20px;
}
#card_white {
    background-color: transparent;
    padding: 0;
    
}
#card_white p{
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
}
.card hr{
    width: 192px;
    border-bottom-width: 0px;
    border-left-width: 0px;
    border-right-width: 0px;
    opacity: 0.25;
    color: #ffffff;
    margin: 0;
}
#line-s10{
    margin-top: 25px;
}
.card-img {
    max-width: 220px;
}
.card-text {
    color: #ffffff;
    font-family: PT Root UI;
    font-size: 16px;
    font-weight: 500;
    line-height: 24px;
    text-align: left;
    margin: 0;
    margin-top: 20px;
    word-break: break-all;
    overflow: auto;
    scrollbar-width: none; /* Для Firefox */
}
.card-text::-webkit-scrollbar {
    display: none;
}

@media (max-width: 720px) {
    
    .design, .design-title, .design-line{
        width: 670px;
        font-size: 30px;
        line-height: 40px;
    }
    .design-cards{
        flex-wrap: wrap;
        gap: 50px 20px;
    }
    .card{
        max-width: 325px;
        max-height: 333px;
    }
    .card-img{
        max-width: 295px;
        max-height: 184px;
    }
    .card-text{
        width: 295px;
        font-size: 14px;
        line-height: 21px;
    }
    .card hr{
        width: 295px;
        border-bottom-width: 0px;
        border-left-width: 0px;
        border-right-width: 0px;
    }
    #card_black img{
        width: 265px;
    }
    #card_white p{
        width: 325px;
    }
}

@media (max-width: 320px){
    .design{
        width: 290px;
        margin: 0px 15px 50px 15px;
    }
    .design-title{
        width: 290px;
        font-size: 22px;
        line-height: 31px;
        margin: 20px 0px 30px 0px;
    }
    .design-line{
        width: 290px;
    }
    .design-cards{
        flex-wrap: wrap;
        gap: 40px 7px;
    }
    .card{
        max-width: 290px;
        max-height: 303px;
    }
    .card-text{
        max-width: 290px;
    }
    #card_black img{
        max-width: 230px;
        max-height: 159px;
    }
    #card_black p{
        max-width: 260px;
        font-size: 14px;
        line-height: 21px;
    }
    #card_black, #card_black hr{
        max-width: 260px;
    }
    .card1{
        order: 1;
    }
    .card2{
        order: 4;
    }
    .card2 .card-text{
        margin: 20px 0px 0px 0px;
    }
    .card3, .card3 .card-text{
        order: 2;
        font-size: 12px;
        line-height: 17px;
    }
    .card4, .card4 .card-text{
        order: 3;
        font-size: 12px;
        line-height: 17px;
    }
    .card3, .card4{
        max-width: 140px;
        max-height: 165px;
    }
    .card3 .card-text,.card4 .card-text{
        max-width: 140px;
    }
    
}
</style>
  