<template>
  <div>
    <Nav></Nav>
    <div class="news-banner"></div>
	  <div class="m-t-90">
          <div class="content">
              <a-row>
                  <a-col :xs="24" :sm="6" :md="6">
                       <ul class="title-nav">
                           <li class="choose">
                               <a href="">
                                   <i class="myIcon about-1 f-l"></i>
                                   <span class="f-l">企业新闻</span>
                               </a>
                           </li>
                           <li>
                               <i class="myIcon about-1 f-l"></i>
                               <span class="f-l">媒体报道</span>
                           </li>
                           <li>
                               <i class="myIcon about-1 f-l"></i>
                               <span class="f-l">生活科普</span>
                           </li>
                           <li>
                               <i class="myIcon about-1 f-l"></i>
                               <span class="f-l">酒文化常识</span>
                           </li>
                       </ul>
                  </a-col>
                  <a-col :xs="24" :sm="18" :md="18">
                      <h1 class="common-h1">企业新闻</h1>
                      <a-row>
                          <a-col :xs="24" :sm="24" :md="6">
                               <div class="news">
                                   <img src="/static/news.jpg" width="100%" alt="">
                                   <h1>企业新闻企业新闻企业新闻企业新闻企业新闻企业新闻</h1>
                                   <p>企业新闻企业新闻企业新闻企业新闻企业新闻企业新闻企业新闻企业新闻</p>
                                   <div>查看全文> </div>
                               </div>
                          </a-col>
                          <a-col :xs="24" :sm="24" :md="18">
                              
                          </a-col>
                      </a-row>
                  </a-col>
              </a-row>
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
	.news-banner{
        width: 100%;
        height: 500px;
        background: url('/static/news-banner.jpg') center no-repeat;
        background-size:100% center;
    }
    .news h1{
        font-size: 18px;
        color:#242424;
        font-weight:bold;
        overflow:hidden;
        text-overflow: ellipsis;
        white-space:nowrap;
    }
    .news p{
        font-size: 14px;
        color:#242424;
        overflow:hidden;
        
    }
</style>
