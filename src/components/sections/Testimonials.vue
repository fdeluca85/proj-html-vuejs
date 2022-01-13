<template>
    <section id="testimonials">
        
        
        <h4>Testimonials</h4>
        <h3>Why do people love me?</h3>

        <div class="row">
            <div class="card">
                <h6>Professional team of specialist and passionate mentor at reach</h6>
                <p>I need to get a certification for English profilency and MaxCoach is my best choice. Their tutors are smart and professional when dealing with students.</p>
                <div class="avatar">
                    <img src="../../assets/img/artist-testimonial-avatar-01.jpg" alt="">
                    <div class="user">
                        <span class="name">Madley Podor</span>
                        <span class="job">/IT Specialist</span>
                    </div>
                </div>
            </div>
            <div class="card active">
                <h6>It's a choice of quality for people with special needs</h6>
                <p>I'm a very strict person so I require everything to be organized and neat. Then, I'll be able to make things right and shine> Max coach guys got me. </p>
                
                <div class="avatar">
                    <img src="../../assets/img/artist-testimonial-avatar-02.jpg" alt="">
                    <div class="user">
                        <span class="name">Florence Themes</span>
                        <span class="job">/Multimedia Admin</span>
                    </div>
                    </div>

            </div>
            <div class="card">
                <h6>The maxCoach team works really hard to ensure high quality</h6>
                <p>I am happy with their arrangement of lesson and subjects. They reflect a scientific investigation in effective methods to be adopted for learners of all levels</p>
                
                <div class="avatar">
                    <img src="../../assets/img/artist-testimonial-avatar-03.jpg" alt="">
                    <div class="user">
                        <span class="name">Luvic Dubble</span>
                        <span class="job">/Private Tutor</span>
                    </div>
                </div>

            </div>
            <div class="card">
                <h6>High level of efficiency and scientific teaching methods</h6>
                <p>I am free to learn at my own peace, follow my own schedule and choose the subject I want to learn from the syllabus. Great study portal for people like me.</p>
                <div class="avatar">
                    <img src="../../assets/img/artist-testimonial-avatar-04.jpg" alt="">
                    <div class="user">
                        <span class="name">Mina Allace</span>
                        <span class="job">/Freelancer</span>
                    </div>
                </div>
            </div>
        </div>
    </section>
  
</template>

<script>
export default {
    name: 'Testimonials'
}
</script>

<style lang="scss" scoped>
section{
    background-color: #faf8f6 ;
    }
.card{
    height: 300px;
    width: 500px;
    background-color: #fff;
    padding: 20px;
    margin: 20px;
    opacity: 60%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
.card:hover{
    opacity: 100%;
}
.avatar{
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 10px;
    padding: 10px;
        
}
.user{
    display: flex;
    flex-direction: column;
        span{
            padding: 5px;
        }
    }
.avatar img{
    height: 100px;
    width: 100px;
    border-radius: 50%;
    
}
p{
    color: #797979;
}
span{
    font-size: 12px;
}

</style>