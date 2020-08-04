<template>
  <div class="about">
    <div class="self">
     <div class="tell">
       <p>{{tale}}}</p>
     </div>
      <div class="pic">
        <img src="../../public/空间站.SVG.png">
      </div>
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
        tale:'团队（Team）是由基层和管理层人员组成的一个共同体，它合理利用每一个成员的知识和技能协同工作，解决问题，达到共同的目标。'+'团队的构成要素总结为5P，分别为目标、人、定位、权限、计划。团队和群体有着根本性的一些区别，群体可以向团队过渡。一般根据团队存在的目的和拥有自主权的大小将团队分为五种类型：问题解决型团队、自我管理型团队、多功能型团队、共同目标型团队、正面默契型团队。\n'
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
    margin-top: 100px;
    float: left;
  }

</style>
