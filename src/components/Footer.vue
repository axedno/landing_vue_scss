<template>
 <footer   class="footer">
        <div class="footer__blockAll">
            <div class="footer__block">
                <div class="footer__cirkul"></div>
                <p class="footer__name">Sama</p>
                <div class="footer__cirkulSmall"></div> 
            </div> 
            <div class="footer__sitemap"> 
                <h4 class="footer__subTitle">Sitemap</h4>
                <p class="footer__text">Home</p>
                <p class="footer__text">Our answer</p>
                <p class="footer__text">Coaching</p>
                <p class="footer__text">Platform</p>
                <p class="footer__text">About Sama</p>
                <p class="footer__text">Coach</p>
                <p class="footer__text">Contact us</p>
                <p class="footer__text">Book a demo <a class="footer__item" href="#"><img src="./../images/icon.png" alt="icon"></a></p>
            </div>
            <div class="footer__social">
                <h4 class="footer__subTitle">Social</h4>
                <p class="footer__text">LinkedIn <a  class="footer__item" href="#"><img src="./../images/icon.png" alt="icon"></a></p>
                <p class="footer__text">Instagram <a  class="footer__item" href="#"><img src="./../images/icon.png" alt="icon"></a></p>
                <p class="footer__text">Facebook <a  class="footer__item" href="#"><img src="./../images/icon.png" alt="icon"></a></p>
                <p class="footer__text">Twitter <a  class="footer__item" href="#"><img src="./../images/icon.png" alt="icon"></a></p>
            </div>
            <div class="footer__get">
                <h4 class="footer__subTitle">Get the app</h4>
                <p class="footer__text">AppStore <a  class="footer__item" href="#"><img src="./../images/icon.png" alt="icon"></a></p>
                <p class="footer__text">Google Play <a  class="footer__item" href="#"><img src="./../images/icon.png" alt="icon"></a></p>
            </div>
        </div>
            <p class="footer__copyr">Copyright © 2021 Sama Europe Ltd. GDPR compliant.</p>
            <p class="footer__location">71-75 Shelton St, Covent Garden, London WC2H 9JQ.</p>
            <p class="footer__end">Terms and Conditions</p>
    </footer> 
    
</template>

<style lang="scss" scoped>

.footer{
    min-height: 695px;
    &__blockAll{
        display: flex;
        justify-content: space-around;
        flex-wrap: wrap;
        margin-top: 100px; 
    }
    &__name{
        font-size: 28px;
        font-weight: 700;
        margin: -28px 0 0 233px;
    }
    &__cirkul{
        height: 29px;
        width: 29px;
        background: pink;
        border-radius: 50%;  
        margin: 0 0 0 200px;
    }
    &__cirkulSmall{
        margin: -3px 0 0 220px ;
        height: 8px;
        width: 8px;
        background: #FF6743;
        border-radius: 50%;
    }
    &__subTitle{
        font-family: Roboto;
        font-style: normal;
        font-weight: normal;
        font-size: 13px;
        line-height: 17px;
        letter-spacing: 1px;
        text-transform: uppercase;
        margin-bottom: 8px;
    }
    &__text{
        font-family: Roboto;
        font-style: normal;
        font-weight: normal;
        font-size: 19px;
        line-height: 29px;
        color: #818788;
    }
    &__sitemap, &__social, &__get{
        position: relative;
    }
    &__item{
        position: absolute;
        margin-top: 5px;
        margin-left: 3px;
    }
    &__copyr{
        font-family: Roboto;
        font-style: normal;
        font-weight: 300;
        font-size: 12px;
        line-height: 26px;
        letter-spacing: 0.3px;
        margin-top: 184px;
        text-align: center;
    }
    &__location{
        font-family: Roboto;
        font-style: normal;
        font-weight: 300;
        font-size: 12px;
        line-height: 26px;
        letter-spacing: 0.3px;
        text-align: center;
    }
    &__end{
        font-family: Roboto;
        font-style: normal;
        font-weight: normal;
        font-size: 16px;
        line-height: 25px;
        color: #818788;
        text-align: center;
        margin: 39px auto;
    }
}


@media all and (max-width: 480px) {
   .footer{
        &__blockAll{
           display: flex;
           flex-direction: column;
        }
        &__text{
           width:200px;
        }
        &__sitemap{
           margin: 20px auto ;
           text-align: center;   
        }
        &__social{  
           margin: 20px auto ;
           text-align: center;
        }
        &__get{
           margin: 20px auto ;
           text-align: center; 
        }
    }
}

</style>