<template>
  <div>
    <van-tabbar v-model="active">
      <van-tabbar-item icon="shop">标签</van-tabbar-item>
      <van-tabbar-item icon="chat">标签</van-tabbar-item>
      <van-tabbar-item icon="records">标签</van-tabbar-item>
      <van-tabbar-item icon="gold-coin">标签</van-tabbar-item>
    </van-tabbar>
  </div>
</template>


<script>
  export default {
    name:"HeadNav",
    data() {
      return {
        active: 0
      }
    }
  }
</script>
