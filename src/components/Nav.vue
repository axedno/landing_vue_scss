<template>
    <nav class="nav">
        <div class="nav__sama">
            <div class="nav__cirkul"></div>  
            <div class="nav__name">Sama</div>
            <div class="nav__cirkulSmall"></div> 
        </div>
        <div class="nav__menu">
            <div class="nav__home">Home</div>
            <div class="nav__how" >How it Works</div>
            <div class="nav__why">Why Sama?</div>
            <div class="nav__about">About Us</div>
            <div class="nav__coach">Coach</div>
            <button class="nav__btn"><span class="nav__book">Book a Demo</span></button>
        </div>
    </nav>
</template>




<style scoped lang="scss">
.nav{
    height: 82px;
    &__sama{
        display: inline-block;
    }
    &__cirkul{
        margin: 23px 0 0px 49.9px;
        height: 29px;
        width: 29px;
        background: pink;
        border-radius: 50%; 
    }
    &__cirkulSmall{
        margin: 0 0 0 73px;
        height: 8px;
        width: 8px;
        background: #FF6743;
        border-radius: 50%;
        position: absolute;
    }
    &__name{
        margin: -26px 0 0 84px;
        font-weight: 700;
        position: absolute;
        font-size: 28px;
    }
    &__menu{
        display: inline-flex;
        justify-content: space-between;
        float: right;
    }
    &__btn{
        background: #007188;
        border-radius: 5px;
        height: 56px;
        width: 145px;
        border: white;
        margin: 13px 48px 0 0;
    }
    &__book{
        font-family: Roboto;
        font-size: 16px;
        font-style: normal;
        font-weight: 700;
        line-height: 26px;
        letter-spacing: 0em;
        text-align: left;
        color:white;  
    }
    &__coach{
        font-family: Roboto;
        font-style: normal;
        font-weight: bold;
        font-size: 16px;
        line-height: 26px;
        font-weight: 700;
        margin: 28px 40px 0 0;
    }
    &__about{
        font-family: Roboto;
        font-style: normal;
        font-weight: bold;
        font-size: 16px;
        line-height: 26px;
        font-weight: 700;
        margin: 28px 40px 0 0;
    } 
    &__why{
        font-family: Roboto;
        font-style: normal;
        font-weight: bold;
        font-size: 16px;
        line-height: 26px;
        margin: 28px 50px 0 0;
        font-weight: 700;
    }
    &__how{
        font-family: Roboto;
        font-style: normal;
        font-weight: bold;
        font-size: 16px;
        line-height: 26px;
        font-weight: 700;
        margin: 28px 40px 0 0;
    }
    &__home{
        font-family: Roboto;
        font-style: normal;
        font-weight: bold;
        font-size: 16px;
        line-height: 26px;
        font-weight: 700;
        margin: 28px 40px 0 0;
    }
}


@media all and (max-width: 480px){
    .nav{
        &__menu{
           display: none;
        } 
    }

}
 

</style>
