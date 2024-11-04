<template>
    <section class="finger">
        <hr class="finger-line">
        <h2 class="finger-title">Съемка видео</h2>
        <div class="finger-cards">
            <img class="finger-cards-img" src="@/assets/img/image 2.jpg" alt="">
            <div class="card">
                <div class="card-info">
                    <img src="@/assets/img/качество_съемки.svg" alt="">
                    <p>Отличное качество съемки новых поколениесмартфонов Samsung позволит создать и смотреть праздники, семейные торжества и памятные моменты на огромном экране, с яркими, живыми цветами и прекрасной детализацией. </p>
                </div>
                <div class="card-info">
                    <img src="@/assets/img/стабилизация.svg" alt="">
                    <p>Дополнительная система стабилизации сделает видеоролики плавными и красивыми.</p>
                </div>
                <div class="card-info">
                    <img src="@/assets/img/замедленная_съемка.svg" alt="">
                    <p>Сверхзамедленная съемка (960 кадров в секунду) теперь в 2 раза дольше. Камера в S10 способна распознать  самое стремительное движение, такое как языки пламени, брызги воды, дым из под колес спорткара.</p>
                </div>
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

.finger {
    height: max-content;
    width: 950px;
    margin: 0px 25px 100px 25px;
}
.finger-line {
    height: 1px;
    opacity: 0.3;
    margin: 0;
}
.finger-title {
    width: 950px;
    height: 40px;
    font-family: PT Root UI;
    margin: 40px 0px 54px 0px;
    font-size: 30px;
    line-height: 40px;
    text-align: left;
}
.finger-cards{
    display: flex;
    flex-direction: row;
    gap: 20px;
}
.finger-cards-img{
    width: 465px;
    height: 248px;
}
.card{
    display: flex;
    flex-direction: column;
    width: 465px;
    gap: 40px;
}
.card-info{
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 21px;
}
.card-info p{
    width: 343px;
    font-family: PT Root UI;
    font-size: 16px;
    font-weight: 500;
    line-height: 24px;
    text-align: left;
    margin: 0;
}
.card-info img{
    margin: 0px 20px 0px 21px;
}

@media (max-width: 720px) {
    .finger{
        width: 670px;
        margin: 0px 25px 100px 25px;
    }
    .finger-title,.finger-line{
        width: 670px;
        font-size: 30px;
        line-height: 40px;
    }
    .card{
        max-height: 521px;
        max-width: 325px;
    }
    .card-info{
        max-width: 325px;
        max-height: 173px;
    }
    .card-info p{
        font-size: 14px;
        line-height: 21px;
    }
    .finger-cards-img{
        max-width: 325px;
        max-height: 173px;
    }
}

</style>
  