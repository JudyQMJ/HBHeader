<template>
	<view class="home_box">
		<gx-header
		 backgroundStyle='background: linear-gradient(to right, #27BEF8, #0047E8);' 
		 title='首页'
		></gx-header>
		<scroll-view scroll-y class="information_box">
			<image src="https://isp-dev.oss-cn-hangzhou.aliyuncs.com/client/other/20190723/f5JnTWQrzA1563847809159.png" mode="" class="wait"></image>
		</scroll-view>
	</view>
	
</template>

<script>
	// import GxHeader from '../components/GxHeader.vue'
	export default{
		name: 'information',
		// components:{GxHeader},
		data() {
			return {}
		},
		onLoad() {
			
		},
		methods: {
			
		},
	}
</script>

<style lang="less" scoped>
	.home_box{
		width: 100%;
		height: 100%;
	}
	.information_box{
		display: flex;
		text-align: center;
		.wait{
			flex: 1;
			margin-top: 30%;
			width: 560upx;
			height: 460upx;
		}
	}
</style>
