<template>
	<view class="uni-page-head">
		<uni-nav-bar left-icon="back" left-text="返回" right-text="菜单" title="导航栏组件"></uni-nav-bar>
	</view>
</template>

<script>
	import uniNavBar from "@/components/uni-nav-bar/uni-nav-bar.vue"
	export default {
		name: 'gxHeader',
		components:{uniNavBar},
		data(){
			return {}
		},
		methods:{}
	}
</script>

<style lang="less" scoped>
</style>
