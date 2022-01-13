<template>
  <div>
    <h5>Explore</h5>
    <ul>
      <li v-for="(exploreLink, index) in exploreLinks" :key="index">
        <a :href="exploreLink.url" class="linkExternal">{{exploreLink.text}}</a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
        name: 'FooterExplore',
        props: {
          exploreLinks: Array
        }


}
</script>

<style lang="scss" scoped>
li{
  padding: 5px;
  }


</style>