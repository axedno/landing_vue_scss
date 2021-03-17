<template>
     <section  class="engement">
        <div class="engement__block">
            <h3 class="engement__subTitle">Elevate engagement</h3>
            <p class="engement__descr" >Our powerful digital platform and proprietary algorithm matches people to the right 
                coach - based on their professional development needs and personal profile.</p>
            <p class="engement__elevate">Elevate engagement</p>
            <p class="engement__delimeter"></p>   
        </div>
        <img class="engement__img" src="./../images/Section.jpg" alt="sama">
    </section>


</template>

<style lang="scss" scoped>
.engement{
    min-height: 827px;
    width: 75%;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    
    &__block{
        margin-top: 140px;
        width: 400px; 
    }
    &__subTitle{
        font-family: Roboto;
        font-style: normal;
        font-weight: bold;
        font-size: 45px;
        line-height: 43px;
    }
    &__descr{
        margin-top: 27px;
        font-family: Roboto;
        font-style: normal;
        font-weight: normal;
        font-size: 24px;
        line-height: 34px;
        letter-spacing: 0.3px;
    }
    &__elevate{
        font-family: Roboto;
        font-style: normal;
        font-weight: 500;
        font-size: 20px;
        line-height: 31px;
        color: #007188;
        margin-top: 30px;
    }
    &__delimeter{
        height: 2px;
        width: 165px;
        background: #007188;
        margin-top: 5px; 
    }
    &__img{
        height: 668px;
        width: 570px;   
    }
}



@media all and (max-width: 480px) {
    .engement{
        &__img{
            display: block;
            margin: 20px auto;
            width: 80%;
            height: 80%;
        }
        &__block{
            display: block;
            margin: 20px auto;
            width: 80%;
            height: 80%;
        }
    }

}
</style>