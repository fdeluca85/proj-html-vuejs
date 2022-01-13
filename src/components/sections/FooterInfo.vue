<template>
<div>
    <h5>Information</h5>
    <ul>
      <li v-for="(info, index) in infos" :key="index">
        <a :href="info.url" class="linkExternal">{{info.text}}</a>
      </li>
    </ul>
  </div>
  
</template>

<script>
export default {
        name: 'FooterInfo',
        props: {
          infos: Array
        }


}
</script>

<style lang="scss" scoped>
li{
  padding: 5px;
  }

</style>