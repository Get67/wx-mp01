<template>
	<view>
	
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			};
		},
    onLoad() {
      const sysInfo = uni.getSystemInfoSync()
      // 可用高度 = 屏幕高度 - navigationBar高度 - tabBar高度 - 自定义的search组件高度
      this.wh = sysInfo.windowHeight - 50
    }
    
	}
</script>

<style lang="scss">

</style>
