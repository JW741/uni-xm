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
	/* 官方组件库 */
	@import 'common/uni.css';
	/* 动画库 */
	@import 'common/animate.css';
	/* 图标样式 */
	@import 'common/icon.css';
	/* 公共样式 */
	@import 'common/common.css'
</style>
