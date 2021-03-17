<template>
    
    <section class="career">
        <div class="career__info">
            <div class="career__one">
                <div id="two"><span class='career__numb'>2</span><span class="career__x">x</span></div><br>
                <div class="career__feature">More inclusive</div>
            </div>
            <div class="career__two">
                <div><span class="career__plus">+</span><span class='career__numb'>65</span> 
                    <span class="career__percent">%</span></div><br>
                <div class="career__feature">Engagement</div>
            </div>
            <div class="career__three">
                <div><span class="career__plus">+</span ><span class='career__numb'>53</span> 
                    <span  class="career__percent">%</span></div><br>
                <div class="career__feature">Productivity</div>
            </div>
            <div class="career__four">
                <div><span class="career__plus">+</span ><span class='career__numb'>80</span>
                    <span  class="career__percent">%</span></div><br>
                <div class="career__feature">Resilience</div>
            </div>
        </div>

        <div class="career__back">
            <p class='career__get'>Getting started is as easy as 1, 2, 3...</p>
            <div class="career__cirkul">
                <div class="career__team">
                    <img id="img1" class="career__cirkul-img" src="./../images/Oval.png" alt="oval">
                    <p class="career__number">1</p>
                    <p class="career__empl">Your company signs <br> up to Sama.</p>
                </div>
                <div class="career__team">
                    <img id="img2" class="career__cirkul-img" src="./../images/Oval(1).png" alt="oval">  
                    <p class="career__number">2</p>
                    <p class="career__empl">Employees match with <br> their professional coach.</p>
                </div>
                <div  class="career__team">
                    <img id="img3" class="career__cirkul-img" src="./../images/Oval(2).png" alt="oval">
                    <p class="career__number">3</p>
                    <p class="career__empl">Employees begin working <br> with their coach via chat, <br> voice or video call.</p>
                </div>
            </div>
            <img class="career__shape" src="./../images/arrow/Promo-decorative-arrow.png" alt="arrow">
        </div>

          
        <div  class="career__infoTwo">
            <img  class="career__section" src="./../images/Section-photo.jpg" alt="section">     
            <div class="career__connect">
                <p class="career__champ"> Champion their <br> career</p>
                <p class="career__employ">Sama connects your employees to the  best professional coach for them. 
                Built to  seamlessly fit into your organisation, and  powered by sophisticated 
                technology and  our team of highly experienced coaches.</p>
                <div>
                    <p class="career__book">Book a demo</p>
                    <p class="career__delimeter"></p>
                </div>
            </div>   
        </div>    
    </section>
</template>

<style lang="scss" scoped>

.career {
    min-height: 1671px;
    position: relative;

    &__info{
        display: flex;
        flex-direction: row;
        justify-content: space-around;
        margin-top: 79px;
        flex-wrap: wrap;
    }
    &__numb{
        font-family: Roboto;
        font-style: normal;
        font-weight: bold;
        font-size: 48px;
        line-height: 62px;
        height: 63px;
    }
    &__x{
        font-family: Roboto;
        font-style: normal;
        font-weight: bold;
        font-size: 24px;
        line-height: 31px;
    }
    &__feature{
        margin-top: -20px;
        font-family: Roboto;
        font-style: normal;
        font-weight: 500;
        font-size: 16px;
        line-height: 25px;
        text-align: center;
        letter-spacing: 0.3px
    }
    &__percent{
        font-family: Roboto;
        font-style: normal;
        font-weight: bold;
        font-size: 24px;
        line-height: 31px;
        text-align: center;
    }
    &__plus{
        font-family: Roboto;
        font-style: normal;
        font-weight: bold;
        font-size: 24px;
        line-height: 31px;
        text-align: center;
        margin-right: 5px;
    }  
    &__back{
        width: 80%;
        margin: 86px auto 0 auto;
        background-image: url('./../images/back/BackgroundBig.png');
        background-repeat: no-repeat;
        background-position: center;  
    }
    &__infoTwo{
        margin-top: 100px;
        width: 90%;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
      
    }
    &__get{
        font-family: Roboto;
        font-style: normal;
        font-weight: bold;
        font-size: 52px;
        line-height: 56px;
        text-align: center;
        padding-top: 115px;
    }
    &__cirkul{   
        display: flex;
        justify-content: space-around;
        padding-top: 70px;
        width: 80%;
        margin: 0 auto;
    }
    &__number{
        margin-top: -60px;
        font-family: Roboto;
        font-style: normal;
        font-weight: normal;
        font-size: 20px;
        line-height: 60px;
        text-align: center;
        color: #002E8C;
    }
    &__empl{
        margin-top: 30px;
        font-family: Roboto;
        font-style: normal;
        font-weight: 300;
        font-size: 21px;
        line-height: 29px;
        text-align: center;
        letter-spacing: 0.3px;
    }
    &__shape{
        display: block;
        margin: 60px 0 0 75%;
    }
    &__section{
        margin: 43px 0 0 150px;  
    }
    &__connect{
        margin-top: 200px;
  
        width: 400px;    
    }
    &__champ{
        font-family: Roboto;
        font-style: normal;
        font-weight: bold;
        font-size: 48px;
        line-height: 43px;
    }
    &__employ{
        font-family: Roboto;
        font-style: normal;
        font-weight: 300;
        font-size: 21px;
        line-height: 34px;
        margin-top: 27px;
        width: 400px;
    }
    &__book{
        font-family: Roboto;
        font-style: normal;
        font-weight: 500;
        font-size: 19px;
        line-height: 31px;
        color: #007188;
        margin-top: 30px;
    }
    &__delimeter{
        height: 2px;
        margin-left: 0px;
        width: 110px;
        background: #007188    
    }
    &__cirkul-img{
        display: block;
        margin: 0 auto;
    }
    &__employ{
        width: 90%;
    }
}
#two{
    margin-left: 35px;
}

@media all and (max-width: 480px) {
    .career{
        &__info{
            margin-bottom: 50px;
        }
        &__get{  
           padding: 0;
           font-size: 40px;
           line-height: 40px;  
        }
        &__back{
           margin: 0 auto 0 auto;    
        }
        &__cirkul{
           display: flex;
           flex-direction: column;
        }
        &__shape{
           display: block;
           margin: 0 auto;
        }
        &__infoTwo{
           display: flex;
           flex-direction: column;
        }
        &__section{
           display: block;
           margin: 50px auto 0 auto;
           width: 80%;
           height: 80%;
        }
        &__connect{
           display: block;
           margin: 0 auto;
           width: 80%;
           height: 80%;
        }  
    }
}
</style>