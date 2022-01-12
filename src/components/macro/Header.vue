<template>
    <header>
        <Countdown />
        <div class="container">
            <div class="logo"><a href=""><img src="../../assets/img/dark-logo.png" alt="logo"></a></div>
            <NavBar :links="links"/>
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
    },
    data () {
        return{
            links:
            [
                {
                    text: "Home",
                    url: "#",
                    current: false

                },
                {
                    text: "Pages",
                    url: "#",
                    current: false

                },
                {
                    text: "Courses",
                    url: "#",
                    current: false

                },
                {
                    text: "Features",
                    url: "#",
                    current: false

                },
                {
                    text: "Blog",
                    url: "#",
                    current: false

                },
                {
                    text: "Shop",
                    url: "#",
                    current: false

                },
            ]
        }
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