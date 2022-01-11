<template>
    <header>
        <Countdown />
        <div class="container">
            <div class="logo"><a href=""><img src="../../assets/img/dark-logo.png" alt="logo"></a></div>
            <NavBar />
            <SocialMedia />
        </div>
        <Hero />
    </header>
  
</template>

<script>
import NavBar from "../elements/NavBar.vue"
import SocialMedia from "../elements/SocialMedia.vue"
import Countdown from "../elements/Countdown.vue"
import Hero from "../elements/Hero.vue"
export default {
    name: 'Header',
    components: {
        NavBar,
        SocialMedia,
        Countdown,
        Hero
    }
}
</script>


<style lang="scss" scoped>
header{
    height: 80px;
    
}
.container{
    justify-content: space-evenly;
    align-items: center;
    .logo img{
        height: 25px;
        cursor: pointer;
    }    
}
</style>