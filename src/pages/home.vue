<template lang="pug">
    //- 测试
    .home {{title}}
      h1.animated.bounceInDown.ease-out.delay-2s.infinite(v-show="true") 555
      van-button(type="warning" class="btn") 危险按钮
      .icon
        van-cell(title="单元格" value="内容" icon="location-o")
</template>
<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      title: 'Welcome to Your Vue.js App'
    }
  }
}
</script>
<style lang="less">
@testcolor: blue;
    .home {
        color: @testcolor;
    };
    .btn {
        color: @testcolor;
    }
    .icon .van-cell{
      background: pink;
    }
      .van-cell__title {
        text-align: left;
      }
</style>
