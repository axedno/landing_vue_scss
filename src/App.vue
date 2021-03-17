<template>
<div>
    <Nav/>
    <Intro/>
    <Career/>
    <Feature/>
    <Engement/>
    <Recall/>
    <Touch/>
    <Footer/>
 
</div>
  
  
</template>

<script>
import Nav from './components/Nav.vue'
import Intro from './components/Intro.vue'
import Career from './components/Career'
import Feature from './components/Feature'
import Engement from './components/Engement'
import Recall from './components/Recall'
import Touch from './components/Touch'
import Footer from './components/Footer'

export default {
  name: 'App',
  components: {
    Nav,
    Intro,
    Career,
    Feature,
    Engement,
    Recall,
    Touch,
    Footer
  }
}
</script>

<style lang="scss">

@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}


input::placeholder {
    width: 134px;
    height: 34px;
    left: 37px;
    top: 23.52px;
    font-family: Roboto;
    font-style: normal;
    font-weight: 500;
    font-size: 18px;
    line-height: 34px;
    letter-spacing: 0.3px;
    padding: 40px;
  }

</style>
