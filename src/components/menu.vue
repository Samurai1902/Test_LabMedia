<template>
    <section class="header">
        <div class="header-menu">
            <div class="menu">
                <div class="menu-img">
                    <img src="@/assets/img/Logo_e.jpg" class="img_e"/>
                    <img src="@/assets/img/Logo_m.jpg" class="img_m"/>
                </div>
                <p class="pc">Название курса в одну строку</p>
            </div>
            <div class="burger">
                <img src="@/assets/img/menu.svg"/>
            </div>
        </div>
        <div class="header-line">
            <hr>
        </div>
        <div class="mobile">
            <p>Samsung Galaxy S10</p>
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
    max-width: 950px;
    display: flex;
    flex-direction: column;
}

.header-line{
    max-width: 950px;
}

.header-line hr{
    max-width: 207px;
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
    max-width: 32px;
    max-height: 32px;
}
 
.menu{
    display: flex;
    flex-direction: row;
    max-width: 854px;
    height: 21px;
    margin: 22px 0px 17px 0px;
    align-items: center;
}

.pc{
    width: 704px;
    height: 21px;
    opacity: 0.7;
    font-family: PT Root UI;
    font-size: 14px;
    line-height: 21px;
    text-align: left;
    margin: 22px 0px 17px 30px;
}

.mobile{
    display: none;
}

.menu-img {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    max-width: 95px;
    max-height: 40px;
    gap: 20px;
    margin: 12px 0px 8px 25px;
}

@media (max-width: 720px) {
    .header{
        max-width: 710px;
    }
    .menu{
        max-width: 600px;
    }
    .pc{
        max-width: 459px;
    }
    .burger{
        margin: 14px 25px 14px 54px;
    }
    .header-line hr{
        max-width: 149px;
    }
    .header-line{
        max-width: 710px;
    }
}

@media (max-width: 320px) {
    .header{
        width: 320px;
        max-height: 74px;
    }
    .header-menu{
        align-items: center;
        max-width: 290px;
    }
    .burger{
        margin: 9px 15px 9px 188px;
    }
    .menu{
        max-width: 70px;
        max-height: 30px;
        margin: 10px 0px 10px 0px;
        max-width: max-content;
    }
    .pc{
        display: none;
        width: 0px;
        height: 0px;
        opacity: 0;
        font-size: 0px;
        line-height: 0px;
        margin: 0;
    }
    .header-line{
        max-width: 320px;
    }
    .header-line hr{
        max-width: 320px;
        height: 1px;
        background: #000000;
        opacity: 0.1;
    }
    .menu-img{
        margin: 9px 0px 9px 15px;
        gap: 15px;
        align-items: center;
    }
    .img_e{
        max-width: 25px;
        max-height: 25px;
    }
    .img_m{
        max-width: 30px;
        max-height: 30px;
    }
    .mobile{
        display: flex;
        width: 320px;
        max-height: 24px;
    }
    .mobile p{
        width: 290px;
        height: 14px;
        opacity: 0.7;
        font-family: PT Root UI;
        font-size: 10px;
        line-height: 14px;
        text-align: left;
        margin: 5px 15px;
    }
}
</style>