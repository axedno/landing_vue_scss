<template>
    
    <section  class="feature">
        <h2 class="feature__insigh">Featured insights</h2>
        <div class="feature__cards">
            <div class="feature__cardsOne">
                <img class="feature__imgOne" src="./../images/Photo.jpg" alt="photo">
                <p class="feature__way">Coaching</p>
                <h3 class="feature__coaching">How coaching helps <br> your team
                    be engaged <br> during the Covid era</h3>
                <p class="feature__date">Published on January 27th, 2021</p>
            </div>
            <div class="feature__cardsTwo">
                <img class="feature__imgTwo" src="./../images/photo(1).jpg" alt="photo">
                <p class="feature__way">Productivity</p>
                <h3 class="feature__coaching">Why coaching should <br> be available 
                    to every <br> employee
                </h3>
                <p class="feature__date">Published on January 12th, 2021</p>
            </div>
            <div class="feature__cardsThree">
                <img class="feature__imgThree" src="./../images/photo(2).jpg" alt="photo">
                <p class="feature__way">Coaching</p>
                <h3 class="feature__coaching">How coaching promotes <br> inclusive teams
                </h3>
                <p id="published" class="feature__date">Published on November 19th, 2020</p>
            </div>
        </div>
        <button class="feature__btn"><span class="feature__btnText">Read all articles</span></button>
    </section>

</template>

<style lang="scss" scoped>
.feature{
    min-height: 1106px;
    background: #F4F9F9;

    &__insigh{
        padding-top: 162px;
        font-family: Roboto;
        font-style: normal;
        font-weight: bold;
        font-size: 51px;
        line-height: 56px;
        text-align: center;
    }
    &__cards{
        display: flex;
        justify-content: space-around;
        margin: 36px auto 0 auto;
        width: 80%;
        flex-wrap: wrap;
    }
 
    &__cardsOne{
        min-height: 574px;
        background: #FFFFFF;
    }
    &__cardsTwo{ 
        min-height: 574px;
        background: #FFFFFF; 
    }
    &__cardsThree{
        min-height: 574px;
        background: #FFFFFF;  
    }
    &__imgOne{
        border-radius: 12px 12px 0px 0px;
    }
    &__imgTwo{
        border-radius: 12px 12px 0px 0px;
    }
    &__imgThree{
        border-radius: 12px 12px 0px 0px;
    }
    &__btn{
        display: block;
        margin: 60px auto 0 auto;
        background: #007188;
        border-radius: 5px;
        height: 58px;
        width: 166px;
        border-color: white;
    }  
    &__btnText{
        font-family: Roboto;
        font-style: normal;
        font-weight: normal;
        font-size: 16px;
        line-height: 18px;
        text-align: center;
        color:white;
    }
    &__way{
        font-family: Roboto;
        font-style: normal;
        font-weight: bold;
        font-size: 13px;
        line-height: 15px;
        letter-spacing: 1.5px;
        text-transform: uppercase;
        color: #FC9C25;
        padding-left: 30px;
        padding-top: 28px;
        background-color: white;
    }
    &__coaching{
        font-family: Roboto;
        font-style: normal;
        font-weight: bold;
        font-size: 27px;
        line-height: 33px;
        padding-left: 30px;
        padding-top: 13px;
        color: #041011;
        background-color: white;
    }
    &__date{
        font-family: Roboto;
        font-style: normal;
        font-weight: normal;
        font-size: 16px;
        line-height: 23px;
        color: #909C9D;
        padding-left: 30px;
        padding-top: 66px;
        background-color: white; 
    }
}
#published{
    padding-top: 99px;
}


@media all and (max-width: 480px) {
    .feature{
        &__cardsOne{
           margin-top: 40px;
        }
        &__cardsTwo{
            margin-top: 40px;
        }
        &__cardsThree{
            margin-top: 40px;
        }
    }

}

</style>