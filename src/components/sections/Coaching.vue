<template>
    <section id="coaching">
        <div class="section_bgc">
            <img src="../../assets/img/artist-shape-01.png" class="shape1" alt="">
            <img src="../../assets/img/maxcoach-shape-14-600x134.png" class="shape14" alt="">

        </div>
        <div class="title">
            <h4>Artist Coaching</h4>
            <h3>I understand what it takes to create.</h3>
            <h3>I can help you with</h3>
        </div>
        <div class="row">
            <div class="card">
                <img src="../../assets/img/artist-box-image-01.png" alt="">
                <h5>Online Courses</h5>
                <p>Online art coaching now offers you a very powerful way to redesign your artist mind.</p>
            </div>
            <div class="card">
                <img src="../../assets/img/artist-box-image-02.png" alt="">
                <h5>One to One</h5>
                <p>Getting the necessary clarity about the current state to help you improve your ability.</p>
            </div>
            <div class="card">
                <img src="../../assets/img/artist-box-image-03.png" alt="">
                <h5>Anywhere</h5>
                <p>Access to valuable and portable program which allow you to setup and live anywhere you want.</p>
            </div>
            <div class="card">
                <img src="../../assets/img/artist-box-image-04.png" alt="">
                <h5>On Time</h5>
                <p>Punctuality is our top priority because it's an essential criteria to assess a program quality.</p>
            </div>        
        </div>
        <div class="row">
            <div class="quote">
                <img src="../../assets/img/artist-quote-icon.png" alt="">
                <h2>I coach and mentor visual artists, like you, to Create Like You Mean It</h2>
                <h4>Martin Garrix</h4>
            </div>
            <div class="text">
                <p>As a coach and mentor, my ultimate goal is to motivate visual artists toward inspired action. I help you get you back on track to being the productive, creative, meaningful and authentic artist you truly want to be.I support artists in crafting and living a creative life as well as feeling good about themselves and their art.</p>
                <p>As an artist and an educator for nearly 30 years, I understand what it takes to create.</p>
                <button>Get started today</button>
            </div>
            
        </div>
        <div class="row">
            <div class="video">
                <a href="#"><img src="../../assets/img/icon-youtube-play.png" class="yt"  alt=""></a>
                <img src="../../assets/img/artist-video-poster.jpg" alt="">
            </div>
        </div>
    </section>
  
</template>

<script>
export default {
    name: 'Coaching'
}
</script>

<style lang="scss" scoped>
section{
    margin: 50px auto;
    width: 70%;
}
.section_bgc{
    position: relative;
    z-index: 1;
    .shape1{
        position: absolute;
        transform: rotatex(180deg);
        left: -400px;
    }
    .shape14{
        position: absolute;
    }
}

.row{
 justify-content: space-evenly;
 z-index: 2;
}
.card{
    padding: 50px;
}
.quote{
    width: 35%;
    padding: 50px;
    text-align: center;
}
.text{
    width: 50%;
    padding: 50px;
    font-weight: lighter;
    p{
        padding-top: 10px;
    }
}
.video{
    position: relative;
    transition: transform .25s, visibility .25s ease-in;
    .yt{
        top: 50%;
        left: 50%;
        position: absolute;
        transform: translate(-50%, -50%);
        
    }
}
.video:hover {
  transform: scale(1.1);
  
}

</style>