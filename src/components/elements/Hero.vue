<template>
    <div class="hero" >
        
        
            <img src="../../assets/img/artist-hero-image-03-204x300.png" class="blc" alt="">
            <img src="../../assets/img/artist-shape-02-768x415.png" class="shapeR" alt="">
            <img src="../../assets/img/artist-shape-01-600x577.png" class="shapeL" alt="">
            <img src="../../assets/img/artist-shape-04.png" class="leaf" alt="">
            <img src="../../assets/img/artist-shape-05.png" class="colors" alt="">

        
       <div class="box">
            <div class="hero__left">
            <img src="../../assets/img/artist-hero-image-01.jpg" class="pictureL" alt="">
            <img src="../../assets/img/artist-hero-image-02-232x300.jpg" class="pictureR" alt="">
        </div>
        <div class="hero__center">
            <div class="title">
                <h4>Hello, I'm Martin</h4>
                <h2>Artist Coaching And Mentoring</h2>
                <h2>Might be for you</h2>
                <button class="btn_orange">Get started today</button>
            </div>
        </div>
        <div class="hero__right">
            <img src="../../assets/img/artist-hero-image-04-235x300.jpg" alt="">

        </div>
       </div>
        
    </div>
  
</template>

<script>
export default {
    name: 'Hero'
}
</script>

<style lang="scss" scoped>
.hero, .box{
    background-color: #FBF9F6;
    height: 600px;
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
    
    &__left, &__right{
    display: flex;
    z-index: 90;
    padding: 50px;
    }
}
.blc{
    position: absolute;
    bottom: 3%;
    left: 30%;
}
.shapeR{
    position: absolute;
    top: 0;
    left: 0;
    z-index: 2;
}

.shapeL{
    position: absolute;
    top: 0;
    right: 100px;
    z-index: 2;
}
.leaf{
    position: absolute;
    top: 5%;
    right: 100px;
    z-index: 3;
}
.colors{
    position: absolute;
    bottom: 5%;
    right: 100px;
    z-index: 3;
}
.pictureL{
    height: 30%;
    position: relative;
    bottom: -120px;
    left: 0%;
    z-index: 5;
    box-shadow: 10px 10px 50px rgb(126, 126, 126);

}

.pictureR{
    position: relative;
    bottom: 100px;
    left: -5%;
    z-index: 4;
    box-shadow: 10px 10px 50px rgb(126,126,126);

}
.title{
    display: flex;
    flex-direction: column;align-items: center;
    justify-content: space-between;
    
}
</style>