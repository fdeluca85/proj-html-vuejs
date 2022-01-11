<template>
    <nav>
        <ul>
            <li>
                <a href="#"><i class="fab fa-twitter"></i></a>
            </li>
            <li>
                <a href="#"><i class="fab fa-facebook-f"></i></a>
            </li>
            <li>
                <a href="#"><i class="fab fa-instagram"></i></a>
            </li>
            <li>
                <a href="#"><i class="fab fa-linkedin"></i></a>
            </li>
        </ul>
    </nav>
  
</template>

<script>
export default {
    name: 'SocialMedia'
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
            font-size: 1.2em;
        }
    }

</style>