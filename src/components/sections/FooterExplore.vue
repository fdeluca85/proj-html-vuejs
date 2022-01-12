<template>
  <div>
    <h5>Explore</h5>
    <ul>
      <li v-for="(exploreLink, index) in exploreLinks" :key="index">
        <a :href="exploreLink.url">{{exploreLink.text}}</a>
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

</style>