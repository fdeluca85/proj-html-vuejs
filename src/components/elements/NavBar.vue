<template>
    <nav>
        <ul>
            <li v-for="(link, index) in links" :key='index'>
                <a :href="link.url">{{link.text}} <i class="fas fa-angle-down"></i></a>
            </li>
            <!-- <li>
                <a href="#">Home <i class="fas fa-angle-down"></i></a>
            </li>
            <li>
                <a href="#">Pages <i class="fas fa-angle-down"></i></a>
            </li>
            <li>
                <a href="#">Courses <i class="fas fa-angle-down"></i></a>
            </li>
            <li>
                <a href="#">Features <i class="fas fa-angle-down"></i></a>
            </li>
            <li>
                <a href="#">Blog <i class="fas fa-angle-down"></i></a>
            </li>
            <li>
                <a href="#">Shop <i class="fas fa-angle-down"></i></a>
            </li> -->
        </ul>
    </nav>
  
</template>

<script>
export default {
    name: 'NavBar',
    props: {
        links: Array
    }
}
</script>

<style lang="scss" scoped>
nav{
    display: flex;
    margin: 5px;
}
ul{
    display: flex;
        li{
            padding: 5px 10px;
            font-size: 1em;
        }
    }

</style>