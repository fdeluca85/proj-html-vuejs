<template>
    <main>
        <Hero />
        <Coaching />
        <Testimonials />
        <Courses />
        <Blog />
        <Events />
        <Newsletter />

    </main>
  
</template>

<script>
import Hero from "../elements/Hero.vue"
import Coaching from "../sections/Coaching.vue"
import Testimonials from "../sections/Testimonials.vue"
import Courses from "../sections/Courses.vue"
import Blog from "../sections/Blog.vue"
import Events from "../sections/Events.vue"
import Newsletter from "../sections/Newsletter.vue"

export default {
    name: 'Main',
    components: {
        Hero,    
       Coaching,
       Testimonials,
       Courses,
       Blog,
       Events,
       Newsletter


    }
}
</script>

<style lang="scss" scoped>


</style>