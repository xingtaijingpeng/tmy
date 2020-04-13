<template>
  <div class="footer">
	  <div class="content">
		  <a-row>
		      <a-col :xs="24" :sm="24" :md="12">酣客酒业有限公司 | 京ICP备 18050664</a-col>
		      <a-col :xs="4" :sm="3" :md="2"><a href="#">关于酣客</a></a-col>
		      <a-col :xs="4" :sm="3" :md="2"><a href="#">酣客产品</a></a-col>
		      <a-col :xs="4" :sm="3" :md="2"><a href="#">酣客文化</a></a-col>
		      <a-col :xs="5" :sm="3" :md="2"><a href="#">酣客研究院</a></a-col>
		      <a-col :xs="4" :sm="3" :md="2"><a href="#">加盟入口</a></a-col>
		      <a-col :xs="24" :sm="3" :md="2"><a href="#">联系我们</a></a-col>
		  </a-row>
	  </div>
    
	
  </div>
</template>

<script>
export default {
  name: 'Footer',
  prop: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
	.footer{
		width: 100%;
		background: #7D1D28;
		color:#fff;
		line-height: 26px;
		padding: 50px 5px;
	}
</style>
