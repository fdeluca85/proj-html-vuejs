<template>
    <header>
        <Countdown />
        <div class="container">
            <div class="logo"><a href=""><img src="../../assets/img/dark-logo.png" alt="logo"></a></div>
            <NavBar />
            <SocialMedia />
        </div>
        
    </header>
  
</template>

<script>
import NavBar from "../elements/NavBar.vue"
import SocialMedia from "../elements/SocialMedia.vue"
import Countdown from "../elements/Countdown.vue"

export default {
    name: 'Header',
    components: {
        NavBar,
        SocialMedia,
        Countdown,
    }
}
</script>


<style lang="scss" scoped>
.container{
    height: 80px;
    justify-content: space-evenly;
    align-items: center;
    .logo img{
        height: 25px;
        cursor: pointer;
    }    
}
</style>