<template>
  <div>
    <h5>Instagram <span>@maxcoach</span></h5>
    <!-- <ul>      
      <li v-for="(image, index) in images" :key="index">
        <img :src="image.url" :alt="image.id">
      </li>
    </ul> -->
    <div class="thumb">
      <img src="../../assets/img/120012142_177596140500760_8623485824101406058_n.jpg" alt="">
      <img src="../../assets/img/120084500_197897808368764_8114555493043279565_n.jpg" alt="">
      <img src="../../assets/img/120099363_364334431619755_7198812647386067017_n.jpg" alt="">
    </div>

  </div>
</template>

<script>
export default {
    name: 'FooterInstagram',
    // props: {
    //       images: Object
    //     }

}
</script>

<style lang="scss" scoped>
.thumb img{
  height: 100px;
  margin: 10px;
}
span{
  color: red;
}

</style>