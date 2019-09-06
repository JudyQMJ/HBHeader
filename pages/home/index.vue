<template>
	<view class="home_box">
		<scroll-view scroll-y class="information_box">
			<image src="https://isp-dev.oss-cn-hangzhou.aliyuncs.com/client/other/20190723/f5JnTWQrzA1563847809159.png" mode="" class="wait"></image>
		</scroll-view>
	</view>
	
</template>

<script>
	export default{
		name: 'information',
		data() {
			return {
				
			}
		},
		onLoad() {
			
		},
		methods: {
			
		},
	}
</script>

<style lang="less">
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
