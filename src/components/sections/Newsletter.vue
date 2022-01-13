<template>
    <section id="newsletter">
        <div class="bgc">
            <img src="../../assets/img/artist-shape-color-paint-top-left-300x170.png" class="tl" alt="">
            <img src="../../assets/img/artist-shape-color-paint-bottom-right-300x153.png" class="br" alt="">
        </div>
        <p class="title_news">Newsletter to get  in touch</p>
        <input type="email" class="email" name="newsletter_email" placeholder="Your e-mail">

    </section>
  
</template>

<script>
export default {
    name: 'Newsletter'
}
</script>

<style lang="scss" scoped>
#newsletter{
    height: 170px;
    background-color: #244186;
    display:flex;
    justify-content: space-around;
    position: relative;
} 
.tl{position: absolute;
        top: 0;
        left: 0;
    }
.br{
    position: absolute;
        bottom: 0;
        right: 0;
}
.email{
    border: none;
    border-bottom:2px solid linen;
    background-color: #244186;
    height: 50px;
    width: 500px;
    color: linen;
    font-size: 16px;
    padding: 20px;
}
p{
    text-align: right;
}
.title_news{
    font-family: 'Times New Roman', Times, serif;
        color: linen;
        font-size: 2em;

}

</style>