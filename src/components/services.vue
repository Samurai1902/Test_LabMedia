<template>
    <section class="service">
        <hr class="service-line">
        <h2 class="service-title">Приложения и сервисы Samsung</h2>
        <div class="service-cards">
            <div class="card card1">
                <img src="@/assets/img/Smart_Switch.svg">
                <p>Благодаря приложению Smart Switch можно перенести информацию со старого смартфона на новый.</p>
            </div>
            <div class="card card2">
                <img src="@/assets/img/Samsung_Health.svg">
                <p class="card-text">Приложение Samsung Health помогает контролировать физическую активность и вести дневник питания.</p>
            </div>
            <div class="card card3">
                <img src="@/assets/img/Bixby.svg">
                <p>Интеллектуальный помощник Bixby обеспечит быстрый доступ к переводчику, поиску в Интернете, покупкам и многому другому.</p>
            </div>
            <div class="card card4">
                <img src="@/assets/img/Samsung_pay.svg">
                <p>Приложение Samsung Pay дает возможность оплачивать свои покупки при помощи смартфона. </p>
            </div>
            <div class="card card5">
                <img src="@/assets/img/SmartThings.svg">
                <p>Благодаря приложению Smart Things можно управлять всеми смарт-устройствами дома.</p>
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

.service {
    height: max-content;
    width: 950px;
    margin: 0px 25px 100px 25px;
}
.service-line {
    height: 1px;
    opacity: 0.3;
    margin: 0;
}
.service-title {
    width: 950px;
    max-height: 40px;
    font-family: PT Root UI;
    margin: 40px 0px 54px 0px;
    font-size: 30px;
    line-height: 40px;
    text-align: left;
}
.service-cards {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: flex-start;
    height: max-content;
}
.card{
    display: flex;
    flex-direction: column;
    align-items: center;
    max-width: 303px;
    max-height: 176px;
    gap: 20px;
}
.card p{
    max-width: 303px;
    max-height: 72px;
    font-family: PT Root UI;
    font-size: 16px;
    line-height: 24px;
    text-align: left;
    margin: 0;
    word-break: keep-all;
    overflow: auto;
    scrollbar-width: none; /* Для Firefox */
}
.card-text::-webkit-scrollbar {
    display: none;
}

.service-cards:nth-child(-n+3){
    gap: 73px 20px;
}

@media (max-width: 720px) {
    .service, .service-title, .service-line{
        width: 670px;
        font-size: 30px;
        line-height: 40px;
    }
    .card{
        max-height: 185px;
        max-width: 210px;
    }
    .service-cards:nth-child(-n+3){
        gap: 61px 20px;
    }
    .card p{
        max-width: 210px;
        font-size: 14px;
        line-height: 21px;
        max-height: 63px;
    }
}

@media (max-width: 320px){
    .service, .service-line{
        width: 290px;
    }
    .service-title{
        width: 290px;
        max-height: max-content;
        font-size: 22px;
        line-height: 31px;
        margin: 20px 0px 30px 0px;
    }
    .service-cards{
        gap: 61px 0px;
        display: flex;
        flex-direction: column;
        align-items: center;
    }
    .card{
        max-width: 290px;
    }
    .card p{
        margin: 0;
        max-width: 205px;
        max-height: 68px;
    }
    .card1, .card1 p, .card3, .card3 p, .card5, .card5 p{
        flex-direction: row;
        gap: 18px;
        font-size: 12px;
        line-height: 17px;
    }
    .card2, .card2 p, .card4, .card4 p{
        flex-direction: row-reverse;
        gap: 18px;
        font-size: 12px;
        line-height: 17px;
    }
}
</style>
  