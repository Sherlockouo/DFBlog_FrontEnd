<template>
  <div class="music">
    <div class="music-player">
      <music-player :musicList="musicList">
        <div name="music-header">
          <music-header></music-header>
        </div>
      </music-player>
    </div>
  </div>
</template>

<script>

  import {getMusicUrl, recommendMusic} from "../apis/data";

  export default {
    name: "Music",
    data() {
      return {
        musicList: [],
        curMusic: ""
      }
    },
    methods: {

    },
    created() {
      this.getRecommendMusic()
      console.log(this.musicList)
    },
    components: {

    }
  }
</script>

<style scoped>
  .music {
    width: calc(100% - 1 * 340px);
    block-size: 100%;
  }

  .music-player {
    width: 100%;
    height: 100%;
    display: flex;
    /*padding: 0 40px 0 40px;*/
    margin-top: 20px;
    float: left;
  }

</style>