<template>
  <div>
    <div class="content logo">
      <img src="/static/logo.png" alt="">
      <div class="nav-right">
        <span class="search"></span>
        <span class="shoppingCart"></span>
      </div>
    </div>
    <div class="nav">
        <div class="content"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Nav',
  prop: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
  .logo{
    height: 140px;
    line-height: 140px;
    border-bottom: 1px solid #ccc;
  }
  .logo img{
      width: 150px;
  }
  .nav-right{
    float: right;
  }
  .shoppingCart{
      display: inline-block;
      width: 30px;
      height: 30px;
      background: url("/static/shoppingCart.png") no-repeat;
      background-size: 30px;
  }
  .search{
    display: inline-block;
    width: 30px;
    height: 30px;
    background: url("/static/search.png") no-repeat;
    background-size: 30px;
  }

  .nav{
    width: 100%;
    height:70px;
    background: #7d1d28;
  }


</style>
