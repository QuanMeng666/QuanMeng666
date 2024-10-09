<script setup>
import {startSakura} from "../src/components/Sakura.js";
</script>

<template>
<div class="blue_bar">
  <div class="white-overlay">
    <h1 style="margin-left: 10% ; margin-top: 7%">
      <span style="font-size: 16px">いぬ</span>
      <span style="font-size: 16px">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ゆめ</span>
      <br>
      <span>犬&nbsp;&nbsp;&nbsp;夢</span>
      <br>
      <span>inuyume</span>
    </h1>
    <div style="margin-left: 10%; margin-top: 3%;" class="p_font">
      <h3>welcome to これです。</h3>
      <h3>inuyume is me.</h3>
      <h3>これは、ぼくの自己紹介のページです。</h3>
      <h3>该页面还在施工中~~~</h3>
    </div>
  </div>
</div>

</template>

<style scoped>
.blue_bar{
  background-color: cyan;
  height: 8px;
  width: auto;
  position: relative;
  border-radius: 10px; /* 添加圆角 */
}
.white-overlay {
  background-color: white;
  height: 30px; /* 根据需要调整高度 */
  width: 100%;
  position: absolute;
  top: 10px; /* 根据需要调整位置 */
  border-radius: 10px; /* 添加圆角 */
}
.p_font{
  font-size: 20px;
  margin: 0;
  font-family: 'Sofia', cursive; /* 更改字体为手写体 */
  color: black; /* 更改文字颜色 */
}
.p_font h3{
  margin-top: 2px; /* 上间距 */
  margin-bottom: 2px; /* 下间距 */
}
</style>
