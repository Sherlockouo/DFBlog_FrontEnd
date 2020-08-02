<template>
  <div class="video">
    <div class="video-player">
      <video-player></video-player>
    </div>
  </div>
</template>

<script>

  export default {
    name: "Video",
    data(){
      return {

      }
    },
    components:{
    }
  }
</script>

<style scoped>
  .video{
    width: calc(100% - 1 * 340px);
    block-size: 100%;
  }
  .video-player{
    width: 100%;
    display: flex;
    padding: 0 40px 0 40px;
    margin-top: 20px;
    float: left;
  }

</style>