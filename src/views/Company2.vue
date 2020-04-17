<template>
  <div>
    <Nav></Nav>
	  <div class="m-t-90">
          <div class="content">
              <a-row>
                  <a-col :xs="24" :sm="6" :md="6">
                       <ul class="title-nav">
                           <li>
                               <a href="">
                                   <i class="myIcon about-1 f-l"></i>
                                   <span class="f-l">公司简介</span>
                               </a>
                               
                           </li>
                           <li class="choose">
                               <i class="myIcon about-1 f-l"></i>
                               <span class="f-l">公司大事记</span>
                           </li>
                       </ul>
                  </a-col>
                  <a-col :xs="24" :sm="18" :md="18">
                      <h1 class="common-h1">公司大事记</h1>
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
	
</style>
