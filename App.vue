<script>
	export default {
		onLaunch: function() {
			console.log('App Launch')
			uni.removeStorageSync('Token')
		},
		onShow: function() {
			console.log('App Show')
		},
		onHide: function() {
			console.log('App Hide')
			
		},
		
	}
</script>

<style>
	/*每个页面公共css */
	@import "@/static/iconfont.css";
</style>
