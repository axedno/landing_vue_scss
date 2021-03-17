<template>
  <section  class="intro">
        <img class="intro__img" src="./../images/sama.jpg" alt="sama">
        <h1 class="intro__name">
            Supercharge your team's  development
        </h1>
        <div class="intro__descr">
            We’re elevating engagement to make the world a better place 
            by bringing the power of executive coaching to be everyone.
        </div>
        <div class="intro__test">
            <input class="intro__input" type="text" placeholder="Your work email">
            <button class="intro__btn"><span class="intro__learn">Learn more</span></button>
        </div>
        <div class="intro__ovalAll">
            <div class="intro__oval"><span class="intro__text">1:1 coaching</span> <img class="intro__line" src="./../images/line.svg" alt="line"></div>
            <div class="intro__oval"><span class="intro__text">Empowering</span>  <img class=" intro__line" src="./../images/line.svg" alt="line"></div>
            <div class="intro__oval"><span  class="intro__text" id='spanThree'>Inclusive</span> <img  class="intro__line" src="./../images/line.svg" alt="line"></div>
        </div>
    </section>
</template>


<style scoped lang="scss">

.intro {
    margin: 0 auto;
    background: #FFF3F1;
    position: relative;
    min-height: 1000px;
    &__name {
        padding: 133px 135px 0 135px;
        font-family: Roboto;
        font-style: normal;
        font-weight: normal;
        font-size: 71px;
        line-height: 71px;
        width: 700px;
        word-wrap:break-word;
    }
    &__descr {
        margin: 43px 0 0 135px;
        font-family: Roboto;
        font-style: normal;
        font-weight: normal;
        font-size: 21px;
        line-height: 34px;
        letter-spacing: 0.3px;
        width: 551px;
    }
    &__input {
        margin: 35px 0 0 135px;
        height: 82px;
        left: 0%;
        right: 0%;
        top: -0.48px;
        background: #FFFFFF;
        border: 1px solid #FFFFFF;
        box-sizing: border-box;
        box-shadow: 0px 24px 32px rgba(0, 0, 0, 0.07);
        border-radius: 200px;
        width: 450px;
        height: 82px; 
    }
    &__btn {
        height: 69px;
        width: 168px;
        background: #007188; 
        border-radius: 200px;
        border: white;
        position: absolute;
        margin: 42px 0 0 -175px;
    }
    &__learn {
        width: 95px;
        height: 34px;
        font-family: Roboto;
        font-style: normal;
        font-weight: 500;
        font-size: 18px;
        line-height: 34px;
        letter-spacing: 0.3px;
        color: #FFFFFF;
    }
    &__ovalAll {
        margin: 35px 0 0 135px;
        height: 35px;
        width: 440px;
    }
    &__text {
        font-family: Roboto;
        font-style: normal;
        font-weight: normal;
        font-size: 14px;
        line-height: 21px;
        padding: 70px;
        margin-top: 10px;
    }
    &__oval {
        border-radius: 50%;
        background-color: #ffddd7;
        height: 30px;
    }
    &__img {
        float: right;
        width: 720px;
        height: 1000px;
    }
    &__line {
        margin-top: 10px;
    }
} 
    
#spanThree {
    padding: 70px 90px 70px 70px;
}


@media all and (max-width: 480px){
  .intro{
        &__img{
            display: block;
            margin: 0 auto;
            float: none;
            width: 60%;
            height: 60%;
        }
        &__name{   
            display: block;
            margin: 0 auto;
            font-size: 60px;
            line-height: 50px;  
            padding:50px 0 0 0;
            width: 80%;
            word-wrap: break-word;
        }  
        &__descr{
            display: block;
            margin: 0 auto;
            font-size: 21px;
            line-height: 34px;
            width: 80%;
            padding-top: 20px;
        }
        &__test{
            width: 100%;
            margin: 0 auto;
            position: relative;
        }
        &__input{
            display: block;
            margin: 20px auto 0 auto;
            width: 80%;
        }
        &__btn{
            width: 30%;
            top: 40%;
            right: 10px;
            transform: translate3d(-45px, -100%, 0);
        }
        &__ovalAll{
            height: 35px;
            width: 80%;
            margin: 20px auto;
        }
        &__line{
            margin-top: 15px;
            width: 20%;
        }
    }

   input::placeholder {
    font-size: 20px;
  }

}
 

</style>