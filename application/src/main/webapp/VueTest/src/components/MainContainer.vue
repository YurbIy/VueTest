<template>
  <div class="mainContainer">
    <BreadCrumps/>
    <Dialog/>
    <MainDisplay/>
  </div>
</template>

<script>
  import BreadCrumps from './BreadCrumps.vue';
  import Dialog from './Dialog.vue';
  import MainDisplay from './MainDisplay.vue';


export default {
  name: 'mainContainer',
  components: {
    BreadCrumps,
    Dialog,
    MainDisplay
  },
  data() {
    return {

    }
  }

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
