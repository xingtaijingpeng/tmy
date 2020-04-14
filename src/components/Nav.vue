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
        <ul class="content">
			<li class="choose">首页</li>
			<li>关于酣客</li>
			<li>新闻资讯</li>
			<li>酣客酱香</li>
			<li>酣客公社</li>
			<li>酣客文化</li>
			<li>联系我们</li>
		</ul>
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
	width: 220px;
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
	margin-left: 30px;
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
.nav ul{
	overflow: hidden;
}
.nav ul li{
	width:10%;
	height:70px;
	background: #7d1d28;
	line-height: 70px;
	text-align:center;
	float:left;
	color:#fff;
    cursor: pointer;
}
.nav ul li.choose{
	background:#5e161e;
}
	
	
</style>
