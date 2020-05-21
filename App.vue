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
	/* 页面容器 */
	page {
		height: 100%;
	}
	
	.container {
		width: 750rpx;
		height: auto;
		font-family: PingFang-SC-Regular;
		font-weight: 400;
		overflow: auto;
	}
	
	.w100 {
		width: 100%;
	}
	
	.h100 {
		height: 100%;
	}
	
	.wh {
		width: 100%;
		height: 100%;
	}
	
	/* 定位 */
	.p-r {
		position: relative;
	}
	
	.p-a {
		position: absolute;
	}
	
	.p-f {
		position: fixed;
	}
	
	/* 弹性布局 */
	.flex {
		display: flex;
	}
	
	.col {
		flex-direction: column;
	}
	
	.fl-w {
		flex-wrap: wrap;
	}
	
	.fl-align {
		align-items: center;
	}
	
	.fl-jc {
		justify-content: center;
	}
	
	.fl-jsb {
		justify-content: space-between;
	}
	
	.fl-jsa {
		justify-content: space-around;
	}
	
	.fl-jse {
		justify-content: space-evenly;
	}
	
	.fl-jsd {
		justify-content: flex-end;
	}
	
</style>
