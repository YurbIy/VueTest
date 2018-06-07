<template>
  <div class="main">
    <Header/>
    <MainContainer/>
  </div>
</template>

<script>
  import Header from './Header.vue';
  import MainContainer from './MainContainer.vue';
  console.log(Header);
export default {
  name: 'Main',
  components: {
    Header,
    MainContainer
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
