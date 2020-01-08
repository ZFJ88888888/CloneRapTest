<template>
  <div class="home">
    <van-swipe :autoplay="1000" indicator-color="hotpink">
      <van-swipe-item>
        <img src="https://img.yzcdn.cn/vant/apple-1.jpg" alt />
      </van-swipe-item>
      <van-swipe-item>
        <img src="https://img.yzcdn.cn/vant/apple-2.jpg" alt />
      </van-swipe-item>
      <van-swipe-item>
        <img src="https://img.yzcdn.cn/vant/apple-3.jpg" alt />
      </van-swipe-item>
      <van-swipe-item>
        <img src="https://img.yzcdn.cn/vant/apple-4.jpg" alt />
      </van-swipe-item>
    </van-swipe>
    <b>Home页面</b>
  </div>
</template>

<script>
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "home",
  data() {
    return {
      images: [
        "https://img.yzcdn.cn/vant/apple-1.jpg",
        "https://img.yzcdn.cn/vant/apple-2.jpg"
      ]
    };
  }
};
</script>
<style scoped>
img {
  height: 200px;
}
</style>