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
import Coaching from "../elements/Coaching.vue"
import Testimonials from "../elements/Testimonials.vue"
import Courses from "../elements/Courses.vue"
import Blog from "../elements/Blog.vue"
import Events from "../elements/Events.vue"
import Newsletter from "../elements/Newsletter.vue"

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