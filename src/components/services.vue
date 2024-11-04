<template>
    <section class="service">
        <hr class="service-line">
        <h2 class="service-title">Приложения и сервисы Samsung</h2>
        <div class="service-cards">
            <div class="card">
                <img src="@/assets/img/Smart_Switch.svg">
                <p>Благодаря приложению Smart Switch можно перенести информацию со старого смартфона на новый.</p>
            </div>
            <div class="card">
                <img src="@/assets/img/Samsung_Health.svg">
                <p>Приложение Samsung Health помогает контролировать физическую активность и вести дневник питания.</p>
            </div>
            <div class="card">
                <img src="@/assets/img/Bixby.svg">
                <p>Интеллектуальный помощник Bixby обеспечит быстрый доступ к переводчику, поиску в Интернете, покупкам и многому другому.</p>
            </div>
            <div class="card">
                <img src="@/assets/img/Samsung_pay.svg">
                <p>Приложение Samsung Pay дает возможность оплачивать свои покупки при помощи смартфона. </p>
            </div>
            <div class="card">
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
    height: 40px;
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
    width: 303px;
    max-height: 176px;
    overflow: auto;
    scrollbar-width: none; /* Для Firefox */
    gap: 20px;
}
.card::-webkit-scrollbar {
    display: none; /* Скрываем скроллбар */
}
.card p{
    width: 100%;
    font-family: PT Root UI;
    font-size: 16px;
    line-height: 24px;
    text-align: left;
    margin: 0;
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
        width: 210px;
    }
    .service-cards:nth-child(-n+3){
        gap: 61px 20px;
    }
    .card p{
        font-size: 14px;
        line-height: 21px;
    }
}

</style>
  