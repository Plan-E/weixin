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

<style lang="scss">
	/*每个页面公共css */
	@import "uview-ui/index.scss";
	view{
		font-size: 28rpx;
		color: #000;
		box-sizing: border-box;
	}
	image{
		display: block;
		height: auto;
	}
</style>
