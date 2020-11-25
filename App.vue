<script>
	export default {
		onLaunch: function() {
			
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
	/* #ifndef APP-NVUE */
	@import "./static/iconfont.css";
	/* #endif */
	/* #ifdef APP-NVUE */
	.iconfont {
		font-family: iconfont;
		font-size: 50upx;
		color: #999999;
	}
	
	/* #endif */
</style>
