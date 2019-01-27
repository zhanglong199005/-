<template>
  <div class="index-container">
    <div class="search-box">
      <input type="text" placeholder="搜索">
      <icon type="search" size="12"></icon>
    </div>
  </div>
</template>

<script>


export default {
  
}
</script>

<style scoped lang="scss">
$uRed:#ff2d4a;
.search-box{
  background-color: $uRed;
  padding: 20rpx 16rpx;
  box-sizing: border-box;
  position: fixed;
  width: 100%;
}
input{
  background-color: white;
  width: 100%;
  box-sizing: border-box;
  padding-left: 376rpx;
  display: block;
  font-size: 24rpx;
  height: 60rpx;
  border-radius: 10rpx;
}
icon{
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%,-50%);
}
</style>
