<template>
    <header>
        <div class="container">
            <img src="../../assets/img/dark-logo.png" alt="logo">
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
    height: 80px;
    display: flex;
    justify-content: space-between;
    line-height: 80px;
    padding: 5px;
    }

</style>