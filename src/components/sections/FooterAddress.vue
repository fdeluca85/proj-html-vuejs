<template>
    <div class="address">
      <h5>Address</h5>
        <p>382 NE 191st St # 87394 Miami, FL 33179-3899 <br>
          +1 (305) 547-9909 (9am - 5pm EST, Monday - Friday)<br>
          support@maxcoach.com
        </p>
      <SocialMedia/>
  </div>

</template>

<script>
import SocialMedia from "../elements/SocialMedia.vue"

export default {
    name: 'FooterAddress',
    components:{
      SocialMedia
    }
}
</script>

<style lang="scss" scoped>
p{
  margin: 10px auto;
  color: grey;
}

</style>