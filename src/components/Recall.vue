<template>
     <section   class="recall">
        <h3 class="recall__subTitle">Don't just take  our word for it</h3>
        <img class="recall__pathOne" src="./../images/arrow/arrow.png" alt="arrow">
        <div class="recall__cardAll">
            <div class="recall__cardOne">
                <div class="recall__starsOne">
                    <img class="recal__starsSize" src="./../images/stars/Shape.svg" alt="star">
                    <img class="recal__starsSize" src="./../images/stars/Shape(1).svg" alt="star">
                    <img class="recal__starsSize" src="./../images/stars/Shape(2).svg" alt="star">
                    <img class="recal__starsSize" src="./../images/stars/Shape(1).svg" alt="star">
                    <img class="recal__starsSize" src="./../images/stars/Shape.svg" alt="star">
                </div>
                <p class="recall__textOne">
                    Each of our team member is getting precious help in their 
                    professional development and can build a program that suit their needs and ambitions.</p>
                <img class="recall__imgSmall" src="./../images/photoSmall(1).jpg" alt="photo">
                <p class="recall__nameOne">Nicolas</p>
                <p class="recall__profOne">COO at CFTE</p>
            </div>
            <div class="recall__cardTwo">
                <div class="recall__starsTwo">
                    <img class="recall__sizeSmall" src="./../images/stars/Shape(1).svg" alt="star">
                    <img class="recall__sizeSmall" src="./../images/stars/Shape.svg" alt="star">
                    <img class="recall__sizeSmall" src="./../images/stars/Shape(1).svg" alt="star">
                    <img class="recall__sizeSmall" src="./../images/stars/Shape.svg" alt="star">
                    <img class="recall__sizeSmall" src="./../images/stars/Shape(1).svg" alt="star">
                </div>
                <p class="recall__textTwo">
                    The design of the Sama app allowed for the digital session to take place seamlessly!
                </p>
                <p class="recall__nameTwo">Vera</p>
                <p class="recall__profTwo">Partnership Associate at CFTE</p>
                </div>
            <div class="recall__cardThree">
                <div class="recall__starsThree">
                    <img class="recall__sizeSmall" src="./../images/stars/Shape.svg" alt="star">
                    <img class="recall__sizeSmall" src="./../images/stars/Shape(1).svg" alt="star">
                    <img class="recall__sizeSmall" src="./../images/stars/Shape(2).svg" alt="star">
                    <img class="recall__sizeSmall" src="./../images/stars/Shape(1).svg" alt="star">
                    <img class="recall__sizeSmall" src="./../images/stars/Shape.svg" alt="star">
                </div>
                <p class="recall__textThree">
                    Sama matched me with a Coach who helped me see that I have exactly
                    what I need to succeed in business (and life)!
                </p>
                <img class="recall__imgSmallTwo" src="./../images/photoSmall(2).jpg" alt="photo">
                <p class="recall__nameThree">Elise Kayfetz</p>
                <p class="recall__profThree">Toronto, Canada</p>
            </div>
        </div>   
    </section>
</template>

<style lang="scss" scoped>
.recall {
    background: #F4F9F9;
    min-height: 1168px;
    &__subTitle{
        width: 410px;
        display: block;
        margin: 0 auto;
        font-family: Roboto;
        font-style: normal;
        font-weight: bold;
        font-size: 52px;
        line-height: 56px;
        padding: 155px 0 0 0;
    }
    &__pathOne{
        display: block;
        margin:  0 auto;
    }
    &__cardAll{
        margin: 0 auto;
        width: 1200px;
        margin-top: 2px;
        position: relative;
    }
    &__cardOne{
        height: 421px;
        width: 525px;
        background-image: url('./../images/back/background.png');
        background-repeat:no-repeat;
    }
    &__starsOne{
        padding: 40px 0 0 53px;
    }
    &__starsSize{
        height: 36px;
        width: 36px;
        display: flex;
        flex-direction: row;
    }
    &__textOne{
        font-family: Roboto;
        font-style: normal;
        font-weight: 300;
        font-size: 28px;
        line-height: 40px;
        letter-spacing: 0.3px;
        padding: 22px 0 0 60px;
    }
    &__imgSmall{
        margin: 35px 0 0 60px;
        height: 65px;
        width: 65px;
    }
    &__nameOne{
        font-family: Roboto;
        font-style: normal;
        font-weight: bold;
        font-size: 16px;
        line-height: 26px;
        margin:-50px 0 0 135px;
       
    }
    &__profOne{
        font-family: Roboto;
        font-style: normal;
        font-weight: normal;
        font-size: 12px;
        line-height: 19px;
        letter-spacing: 1px;
        text-transform: uppercase;
        color: #818788;
        margin:0 0 0 135px;
    }
    &__cardTwo{
        background-image:url('./../images/back/background1.png');
        background-repeat:no-repeat;
        height: 298px;
        width: 523px;
        float: right;
        margin: -420px 120px 0 0;
    }
    &__starsTwo{
        display: flex;
        flex-direction: row;
        padding: 60px 0 0 60px;
    }
    &__sizeSmall{
        height: 26px;
        width: 26px;
    }
    &__textTwo{
        font-family: Roboto;
        font-style: normal;
        font-weight: 300;
        font-size: 18px;
        line-height: 29px;
        letter-spacing: 0.3px;
        padding: 23px 0 0 60px;
        width: 400px;
    }
    &__nameTwo{
        padding: 10px 0 0 79px;
        font-style: normal;
        font-weight: bold;
        font-size: 17px;
        line-height: 26px;
    }
    &__profTwo{
        padding: 15px 0 0 73px;
        font-style: normal;
        font-weight: normal;
        font-size: 12px;
        line-height: 19px;
        letter-spacing: 1px;
        text-transform: uppercase;
    }
    &__cardThree{
        width: 523px;
        height: 328px;
        background-image:url('./../images/back/background2.png');
        margin: -100px 0 0 550px;
    }
    &__starsThree{
        padding: 58px 0 0 53px;
    }
    &__textThree{
        font-family: Roboto;
        font-style: normal;
        font-weight: 300;
        font-size: 21px;
        line-height: 29px;
        letter-spacing: 0.3px;
        padding: 14px 0 0 58px;
        width: 400px;
    }
    &__imgSmallTwo{
        height: 44px;
        width: 44px;
        padding: 27px 0 0 58px;
    }
    &__nameThree{
        font-style: normal;
        font-weight: bold;
        font-size: 16px;
        line-height: 26px;
        margin: -45px 0 0 110px;
    }
    &__profThree{
        font-style: normal;
        font-weight: normal;
        font-size: 12px;
        line-height: 19px;
        letter-spacing: 1px;
        text-transform: uppercase;
        margin-left: 110px;
    }
}

@media all and (max-width: 480px) {
    .recall{
        &__cardAll{
            display: flex;
            flex-direction: column;
            flex-wrap: wrap;
            width: 100%;
            margin: 0 auto;
        }
        &__cardOne{
            width: 400px;
            height: 120%;
            margin: 0 auto;
            padding: 0;
        }
        &__imgSmall{
             margin-bottom: 20px;
        }
        &__cardTwo{
            float: none;
            margin: 20px auto 0 auto;
            width: 80%;
        }
        &__cardThree{
            margin:20px auto 20px auto;
            width: 80%;  
        }
        &__textOne{
            width: 80%;
            font-size: 22px;
        }
        &__textTwo{
            width: 80%;
        }
        &__textThree{
            width: 80%;
        }
        &__nameOne{
            margin-top: -70px;
        }
        &__profOne{
            padding-bottom: 50px;
        }
        &__starsOne{
            margin-top: -30px;
        }  
        &__starsThree{
            margin-top: -30px;
        }     
    }

}


</style>