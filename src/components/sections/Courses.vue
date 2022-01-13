<template>
    <section id="courses">
        <div class="container">
            <div class="title">
                <h4>Artist Coaching</h4>
                <h3>Lastest online Courses</h3>
            </div>
            <div class="box">
                <div class="card">
                    <img src="../../assets/img/artist-course-08-480x480.jpg" class="paint" alt="corse paint color">
                    <div class="cardInfo">
                        <span class="price">$18.00</span>
                    <span class="name">The Acrylic Painting Academy</span>
                    <span class="info"><i class="far fa-file-alt"></i> 4 Lesson  <i class="far fa-user"></i> 50 Sudents</span>
                    </div>
                </div>
                <div class="card">
                    <img src="../../assets/img/artist-course-07-480x480.jpg" class="paint" alt="corse paint color">
                    <div class="cardInfo">
                        <span class="price">$21.00</span>
                    <span class="name">Drawing an Shading: <br> Complete Course</span>
                    <span class="info"><i class="far fa-file-alt"></i> 4 Lesson  <i class="far fa-user"></i> 50 Sudents</span>
                    </div>
                </div>
                <div class="card">
                    <img src="../../assets/img/artist-course-06-480x480.jpg" class="paint" alt="corse paint color">
                    <div class="cardInfo">
                        <span class="price">$19.00</span>
                        <span class="name">The Color Theory for Digital Artist</span>
                        <span class="info"><i class="far fa-file-alt"></i> 4 Lesson  <i class="far fa-user"></i> 50 Sudents</span>
                    </div>
                </div>
                <div class="card">
                    <img src="../../assets/img/artist-course-05-480x480.jpg" class="paint" alt="corse paint color">
                    <div class="cardInfo">
                        <span class="price">$35.00</span>
                        <span class="name">Ultimate Guide to Digital <br> Sketching for Beginner</span>
                        <span class="info"><i class="far fa-file-alt"></i> 14 Lesson  <i class="far fa-user"></i> 50 Sudents</span>
                    </div>
                </div>
                <div class="card">
                    <img src="../../assets/img/artist-course-04-480x480.jpg" class="paint" alt="corse paint color">
                    <div class="cardInfo">
                        <span class="price">$19.00</span>
                        <span class="name">Portrait Drawing The <br> Smart Way</span>
                        <span class="info"><i class="far fa-file-alt"></i> 2 Lesson  <i class="far fa-user"></i> 50 Sudents</span></div>
                </div>
                <div class="card">
                    <img src="../../assets/img/artist-course-03-480x480.jpg" class="paint" alt="corse paint color">
                    <div class="cardInfo">
                        <span class="price">$19.00</span>
                        <span class="name">Mastering Watercolor <br> Painting from Beginner</span>
                        <span class="info"><i class="far fa-file-alt"></i> 9 Lesson   <i class="far fa-user"></i> 50 Sudents</span>
                    </div>
                </div>
                <div class="card">
                    <img src="../../assets/img/artist-course-02-480x480.jpg" class="paint" alt="corse paint color">
                    <div class="cardInfo">
                        <span class="price">$25.00</span>
                        <span class="name">The Art & Science of Drawing</span>
                        <span class="info"><i class="far fa-file-alt"></i> 4 Lesson   <i class="far fa-user"></i> 50 Sudents</span>
                    </div>
                </div>
                <div class="card">
                    <img src="../../assets/img/artist-course-01-480x480.jpg" class="paint" alt="corse paint color">
                    <div class="cardInfo">
                        <span class="price">$22.00</span>
                        <span class="name">The Colored Pencil <br> Drawing Corse</span>
                        <span class="info"><i class="far fa-file-alt"></i> 6 Lesson  <i class="far fa-user"></i> 50 Sudents</span>
                    </div>

                </div>
                <button class="btn_reverse">View all Courses <i class="fas fa-long-arrow-alt-right"></i></button>
                
            </div>
            
        </div>
    </section>
  
</template>

<script>
export default {
    name: 'Courses'
}
</script>

<style lang="scss" scoped>
.container{
    flex-direction: column;
    justify-content: center;
}
.box{
    padding-top: 20px;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    // padding: 10px;
}
.card{
         height: 500px;
         

}

.card, .cardInfo, .paint{
    display: flex;
    flex-direction: column;
     transition: 0.6s ;
     overflow: hidden;
    img{
        height: 350px;
        width: 350px;
        
    }
}
.cardInfo{
    padding: 10px;
}
.cardInfo:hover{
        cursor: pointer;
        transform: scale(1.1);
        background-color: #fff;
        border: 2px solid #ef6f31;
        padding: 20px 20px;
        transform: translatey(-60%);
        width: 90%;
        height: 150px ;
}
.price{
    color: #ef6f31;
}
.info{
    color: lightgrey;
       
}
span{
    padding: 5px;
}
</style>