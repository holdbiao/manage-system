<template>
<div class="header-wrapper">
    <div class="left-wrapper">
       <div class="flex-button">
       <i class="el-icon-menu"></i>
       </div>
       <div class="name">后台管理系统</div>
    </div>
</div>
</template>

<script>
export default {
  name: 'home',
  data () {
    return {
      msg: 'head-wrapper'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
$main-color: #242f42;
.header-wrapper {
  height: 60px;
  background-color: $main-color;
  & .flex-button {
      float: left;
      width: 60px;
      height: 100%;
      text-align: center;
      line-height: 60px;
    & i {
      font-size: 30px;
      color: #fff;
      line-height: 60px;
    }
  }
  .name {
      display: inline-block;
      height: 60px;
      line-height: 60px;
      font-size: 20px;
      color: #fff;
  }
}
</style>
