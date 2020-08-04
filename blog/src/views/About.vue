<template>
  <div class="about">
    <div class="self">
      <p>sdfajskbfhfbasdasd</p>
    </div>
  </div>
</template>

<script>

  export default {
    name:'About',
    props:{

    },
    data(){
      return {

      }
    },
    components:{
    }
  }
</script>

<style scoped>

  html,body{
    display: block;
    width: 100%;
    height: 100%;
  }

  .about{
    width: calc(100% - 1 * 340px);
    height: 100%;
    block-size: 100%;
  }

  .self{
    width: 100%;
    height: 100%;
    padding: 0 20px 0 20px;
    margin-top: 20px;
    float: left;
  }

</style>
