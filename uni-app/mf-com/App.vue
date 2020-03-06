<script>
	export default {
		onLaunch: function() {
			console.log('App Launch')
		},
		onShow: function() {
			console.log('App Show')
		},
		onHide: function() {
			console.log('App Hide')
		}
	}
</script>

<style>
	/*每个页面公共css */
	/*官方样式库*/
	@import url("./common/uni.css");
	/*自定义图标库*/
	@import url("./common/icon.css");
	/*引用动画库*/
	@import url("./common/animate.css");
</style>
