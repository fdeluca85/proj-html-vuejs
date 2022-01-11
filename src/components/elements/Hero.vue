<template>
    <div class="hero" >
        <div class="heroLeft">

            <img src="../../assets/img/artist-hero-image-01.jpg" alt="">
            <img src="../../assets/img/artist-hero-image-02-232x300.jpg" alt="">
        </div>
        <div class="heroCenter">
            <div class="title">
                <h3>Hello, I'm Martin</h3>
                <h2>Artist Coaching And Mentoring</h2>
                <h2>Might be for you</h2>
                <button>Get started today</button>
            </div>
        </div>
        <div class="heroRight">
            <img src="../../assets/img/artist-hero-image-04-235x300.jpg" alt="">

        </div>
        
    </div>
  
</template>

<script>
export default {
    name: 'Hero'
}
</script>

<style lang="scss" scoped>
.hero{
    background-color: #FBF9F6;
    background-image: url('../../assets/img/artist-hero-image-03-204x300.png');
    background-repeat: no-repeat;
    background-position: bottom center;
    height: 600px;
    padding: 20px;
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.heroLeft{
    display: flex;
}
.title{
    display: flex;
    flex-direction: column;align-items: center;
    justify-content: space-between;
    
}
</style>