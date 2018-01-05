<template>
  <div class="index">
   <p id="header">{{date}}</p>
   <h2>asasdasds
     <span>asdasda</span>
   </h2>
   <p id="test">adadadasd</p>
  </div>
</template>

<script>
export default {
  data () {
    return {
      date:'index'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="less">
@import '../assets/less/less.less';
@color: #4D926F;

#header {
  color: @titlefontcolor;
}
h2 {
  color: @color;
  span{
    color: red;
  }
}
</style>


