<template>
  <div class="mySpace">
    <div class="conten">
      <div class="left_box">
        <img src="../../assets/img/home1.jpg" alt="">
      </div>
      <div class="right_box">

      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: '',
    components: {},
    data () {
      return {}
    },
    mounted(){

    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="stylus" rel="stylesheet/stylus">
  .mySpace {
    padding-top: 30px;
    height: 100%
    max-width: 90%;
    min-width: 90%;
    overflow hidden;
    display: flex;
    justify-content: center;
    align-items: center;
    .conten {
      background-color: #fff
      width: 912px;
      height: 574px;
      img {
        width: 150px;
        height: 140px;
      }
    }
    .left_box {
      width: 212px;
      height: 100%;
      floa: left;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .right_box {
      width: 700px
      floa: left;
      background-color: skyblue
      height: 100%;
    }
  }
</style>
