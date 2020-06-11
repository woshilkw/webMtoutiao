<!--  -->
<template>
  <div class="tt-header">
    <div class="header-nav">
      <div class="nav-left">
        <div class="left-app">下载APP</div>
        <div class="left-register">注册头条号</div>
      </div>
      <div class="nav-right">
        <div class="right-item">发文</div>
        <div class="right-item">反馈</div>
        <div class="right-item">侵权投诉</div>
        <div class="right-item">头条产品</div>
      </div>
    </div>
  </div>
</template>

<script>
//这里可以导入其他文件（比如：组件，工具js，第三方插件js，json文件，图片文件等等）
//例如：import 《组件名称》 from '《组件路径》';

export default {
  //import引入的组件需要注入到对象中才能使用
  components: {},
  data() {
    //这里存放数据
    return {};
  },
  //监听属性 类似于data概念
  computed: {},
  //监控data中的数据变化
  watch: {},
  //方法集合
  methods: {},
  //生命周期 - 创建完成（可以访问当前this实例）
  created() {},
  //生命周期 - 挂载完成（可以访问DOM元素）
  mounted() {},
  beforeCreate() {}, //生命周期 - 创建之前
  beforeMount() {}, //生命周期 - 挂载之前
  beforeUpdate() {}, //生命周期 - 更新之前
  updated() {}, //生命周期 - 更新之后
  beforeDestroy() {}, //生命周期 - 销毁之前
  destroyed() {}, //生命周期 - 销毁完成
  activated() {} //如果页面有keep-alive缓存功能，这个函数会触发
};
</script>
<style lang='less' scoped>
  .tt-header {

    .header-nav {
      width: 100vw;
      height: 30px;
      line-height: 30px;
      display: flex;
      justify-content: space-between;
      background-color: black;
      color: #a6a6a6;
      font-size: 14px;
      .nav-left {
        text-align: center;
        display: flex;
       
        .left-app {
          width: 75px;
          border-right: 1px solid #3a3a3a;
        }

        .left-register {
           width: 90px;
        }
      }

      .nav-right {
        display: flex;
        .right-item {
          width: 75px;
          text-align: center;
          border-right: 1px solid #3a3a3a;
        }
      }
    }
  }
</style>