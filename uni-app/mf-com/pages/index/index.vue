<template>
	<view>

		<!--view class="iconfont icon-daohanglan-03" style="margin-top:200rpx;display:flex;justify-content: center; font-size: 100rpx;color: red;">
		</view-->
		<view style="display:flex;justify-content: center;padding: 100rpx;">
			<view class="animated " hover-class="bounceIn" style="font-size: 100rpx;color: red;">
				{{contents}}
			</view>
		</view>

	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello',
				contents:'World',
			}
		},
		onLoad() {
			
		},
		methods: {

		}
	}
</script>

<style>

</style>
