<template>
  <div class='foorNav'>
    <van-tabbar route>
      <van-tabbar-item
        replace
        to="/home"
        icon="home-o"
      >
        标签
      </van-tabbar-item>
      <van-tabbar-item
        replace
        to="/search"
        icon="search"
      >
        标签
      </van-tabbar-item>
    </van-tabbar>
	</div>
</template>

<script>
export default {
  name: 'foorNav',
  data() {
    return {
    }
  },
	methods:{
	}
}
</script>
<style lang='less' scoped>
	// .foorNav{
	// }
</style>
