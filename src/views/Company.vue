<template>
  <div>
    <Nav></Nav>
	  <div class="m-t-90">
		  <a-row class="content" >
			  <a-col :xs="24" :sm="6" :md="6">

			  </a-col>
			  <a-col :xs="24" :sm="18" :md="18">
				  <h1 class="common-h1">公司介绍</h1>
				  <div class="common-p">
					  <p>原标题：习近平同印度尼西亚总统佐科就中印尼建交70周年互致贺电</p>
					  <p>习近平在贺电中指出，中国和印尼友好交往源远流长。建交70年来，双边关系取得长足发展。特别是近年来，两国关系定位不断提升，合作领域不断拓展，共建“一带一路”成果丰硕，在国际和地区事务中密切配合，给两国人民带来福祉，为地区和全球的繁荣稳定作出重要贡献。</p>
				  </div>
				  <h2 class="common-h2">愿景</h2>
			  </a-col>
		  </a-row>
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
