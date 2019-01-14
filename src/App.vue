<script>
	export default {
		onLaunch: function () {
			console.log('App Launch')
		},
		onShow: function () {
			console.log('App Show')
		},
		onHide: function () {
			console.log('App Hide')
		}
	}
</script>

<style>
	@import './common/uni.css';
	/*每个页面公共css */
	image{
		max-width: 100%;
	}
	.uni-image {
	    width: -webkit-fill-available;
	    height: 240upx;
	    display: contents;
	    overflow: hidden;
	}
	.top-view{
		margin-top: 44upx;
		padding: 10upx;
	}
</style>
