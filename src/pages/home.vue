<template>
	<div class="home">
		<!-- <tag /> -->
		<Carousel/>
		<CFlow/>
	</div>
</template>

<script>
	import Carousel from '@/components/CCarousel/Carousel'//轮播图
	import CFlow from '@/components/WaterFlow/Flow'//瀑布流
	import friend from '@/components/friend'
	import tag from '@/components/tag'

	//瀑布流数据
	const content = [{
    title:'无版权限制的高清大图素材网站',
    img:'',
    cont:'最近收集了一波免费图片网站，相比于搜索出来的动不动就是版权限制，质量堪忧的图片，真是甩了好几条街了，分享给大家，大家有需要自取吧，每个网站提供的图片类型和质量都不一样，大家可以找合适自己的。',
	footCont:'哇答西捏咩哟哇：精神小伙',
	

}]

	export default {
		name: 'home',
		components: {
			friend,
			tag,
			Carousel,
			CFlow
		}
	}
</script>
<style scoped>

</style>