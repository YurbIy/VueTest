<template>
  <div class="header">
    <div class="mainHeader">
      <div class="title">
        <h2>{{title}}</h2>
      </div>
      <div class="user">
        user: {{user}}
      </div>
    </div>
    <div class="getHelp">
      Get help!
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
  data() {
    return {
      title: 'MPDA',
      user: 'user'
    }
  }

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .header {
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    justify-content: space-between;
  }
  .mainHeader {
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    align-content: stretch;
    width: 74%;
    text-align: left;
    border-bottom-style: solid;
    border-bottom-color: #EC8026;
    border-bottom-width: 7px;
    color: #EC8026;
  }
  .title {
    width: 80%
  }
  .getHelp {
    text-align: right;
    width:24%;
    border-bottom-style: solid;
    border-bottom-color: #FCAF17;
    border-bottom-width: 7px;
    color: #EF8065;
  }
  .user {
    text-align: right;
    width: 20%;
    color: #E44C16;
  }
h1, h2 {
  font-weight: normal;
  margin: 0;
}
</style>
