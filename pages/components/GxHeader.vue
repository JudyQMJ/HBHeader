<template>
	<view class="gx_header" :style='backgroundStyle'>
		<uni-nav-bar fixed='true' status-bar="true" :left-icon="leftIcon" :left-text="leftText" :title="title"></uni-nav-bar>
	</view>
</template>

<script>
	import uniNavBar from "@/components/uni-nav-bar/uni-nav-bar.vue"
	export default {
		name: 'gxHeader',
		components:{uniNavBar},
		props:{
			leftText: {
				type: String,
				default: ''
			},
			title: {
				type: String,
				default: ''
			},
			leftIcon: {
				type: String,
				default: 'back'
			},
			backgroundStyle:{
				type: String,
				default: ''
			}
		},
		data(){
			return {}
		},
		methods:{}
	}
</script>

<style lang="less" scoped>
	.gx_header{
		uni-nav-bar, .uni-navbar, .uni-navbar__content, /deep/ .uni-navbar, /deep/.uni-navbar__content{
			background: inherit !important;
		}
	}
</style>
