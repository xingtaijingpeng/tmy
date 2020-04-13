<template>
  <div>
    <Nav></Nav>
	<!-- banner -->
	<a-carousel autoplay>
	    <div><h3>1</h3></div>
	    <div><h3>2</h3></div>
	    <div><h3>3</h3></div>
	    <div><h3>4</h3></div>
    </a-carousel>
    <!-- banner 结束 -->
	<h1 class="title">从源头开始 走进酣客</h1>
	<div class="content source"></div>
	
	<h1 class="title">酣客资讯 企业动态</h1>
	<div class="content news">
		<div class="left">
			<img src="/static/news.jpg" width="100%" height="100%" alt="">
		</div>
		<div class="right">
			<ul>
				<li>
					<span class="font">百度新闻是包含海量资讯的新闻服务平台,真实反映每时每刻的新闻热点</span>
					<span class="time">【2019.11.12】</span>
				</li>
				<li>
					<span class="font">百度新闻是包含海量资讯的新闻服务平台,真实反映每时每刻的新闻热点</span>
					<span class="time">【2019.11.12】</span>
				</li>
				<li>
					<span class="font">百度新闻是包含海量资讯的新闻服务平台,真实反映每时每刻的新闻热点</span>
					<span class="time">【2019.11.12】</span>
				</li>
				<li>
					<span class="font">百度新闻是包含海量资讯的新闻服务平台,真实反映每时每刻的新闻热点</span>
					<span class="time">【2019.11.12】</span>
				</li>
				<li>
					<span class="font">百度新闻是包含海量资讯的新闻服务平台,真实反映每时每刻的新闻热点</span>
					<span class="time">【2019.11.12】</span>
				</li>
				<li>
					<span class="font">百度新闻是包含海量资讯的新闻服务平台,真实反映每时每刻的新闻热点</span>
					<span class="time">【2019.11.12】</span>
				</li>
			</ul>
			<div class="more"> 更多> </div>
		</div>
		
		
	</div>
	<Footer></Footer>
  </div>
</template>

<script>
	/* 
	 
	 <a-row>
	     <a-col :xs="24" :sm="6" :md="6">
	 		
	 	</a-col>
	     <a-col :xs="24" :sm="18" :md="18"></a-col>
	 </a-row>
	 
	 */
// @ is an alias to /src

import Nav from '@/components/Nav'
import Footer from '@/components/Footer'
export default {
  name: 'Home',
  components: {
    Nav,Footer
  }
}
</script>
<style>
	.slick-slide {
	  text-align: center;
	  height:990px;
	  line-height: 990px;
	  background: #364d79;
	  overflow: hidden;
	}
	
	.slick-slide h3 {
	  color: #fff;
	}
	
	.source{
		height: 690px;
		background: #364D79;
	}
	
	.news{
		overflow: hidden;
	}
	.news .left{
		width: 430px;
		height:300px;
		float:left;
		margin-bottom: 150px;
	}
	.news .right{
		width: calc(100% - 660px);
		margin-left: 30px;
		float:left;
		height: 300px;
		overflow: hidden;
		margin-bottom: 150px;
	}
	.news .right .more{
		display: inline-block;
		width: 100%;
		color:#7d1d28;
		font-weight: bold;
		text-align: right;
	}
	.news .right li{
		list-style: disc;
		margin-left:30px;
		margin-bottom: 15px;
		color:#373737;
	}
	.news .right li .font{ 
		width: calc(100% - 100px);
		float: left;
		overflow: hidden;
		text-overflow: ellipsis;
		white-space: nowrap;
	}
	.news .right li .time{ 
		width: 100px;
		float: left;
		text-align: right;
	}
	
	
</style>
