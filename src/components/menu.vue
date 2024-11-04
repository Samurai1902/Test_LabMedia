<template>
    <section class="header">
        <div class="header-menu">
            <div class="menu">
                <div class="menu-img">
                    <img src="@/assets/img/Logo_e.jpg"/>
                    <img src="@/assets/img/Logo_m.jpg"/>
                </div>
                <p>Название курса в одну строку</p>
            </div>
            <div class="burger">
                <img src="@/assets/img/menu.svg"/>
            </div>
        </div>
        <div class="header-line">
            <hr>
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

.header{
    width: 950px;
    display: flex;
    flex-direction: column;
}

.header-line{
    width: 950px;
}

.header-line hr{
    width: 207px;
    height: 3px;
    background: #D70E2A;
    margin: 0;
    border-bottom-width: 0px;
    border-left-width: 0px;
    border-right-width: 0px;
}

.header-menu{
    display: flex;
    flex-direction: row;
}

.burger{
    margin: 14px 25px 14px 89px;
}
 
.menu{
    display: flex;
    flex-direction: row;
    width: 854px;
    height: 21px;
    margin: 22px 0px 17px 0px;
    align-items: center;
}

.menu p{
    width: 704px;
    height: 21px;
    opacity: 0.7;
    font-family: PT Root UI;
    font-size: 14px;
    line-height: 21px;
    text-align: left;
    margin: 22px 0px 17px 30px;
}

.menu-img {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    width: 95px;
    height: 40px;
    margin: 12px 0px 8px 25px;
}

@media (max-width: 720px) {
    .header{
        width: 710px;
    }
    .menu{
        width: 600px;
    }
    .menu p{
        width: 459px;
    }
    .burger{
        margin: 14px 25px 14px 54px;
    }
    .header-line hr{
        width: 149px;
    }
    .header-line{
        width: 710px;
    }
}
</style>