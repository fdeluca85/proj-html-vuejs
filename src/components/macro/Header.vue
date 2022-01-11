<template>
    <header>
        <div class="container">
            <div class="logo"><img src="../../assets/img/dark-logo.png" alt="logo"></div>
            <NavBar />
            <SocialMedia />
        </div>
    </header>
  
</template>

<script>
import NavBar from "../elements/NavBar.vue"
import SocialMedia from "../elements/SocialMedia.vue"
export default {
    name: 'Header',
    components: {
        NavBar,
        SocialMedia       

    }
}
</script>

<style lang="scss" scoped>
header{
    height: 50px;
    
}
.container{
    justify-content: space-evenly;
    align-items: center;
    .logo img{
        height: 25px;
}
   
    
}



</style>