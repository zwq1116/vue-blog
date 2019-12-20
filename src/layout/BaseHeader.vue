<template>
  <el-menu mode="horizontal" background-color="#1b1c1d">
    <el-menu-item><h2 class="blog"> Blog</h2></el-menu-item>
    <el-menu-item class="el-icon-s-home"> 首页</el-menu-item>
    <el-menu-item class="el-icon-s-grid"> 分类</el-menu-item>
    <el-menu-item class="el-icon-s-flag"> 标签</el-menu-item>
    <el-menu-item class="el-icon-folder"> 归档</el-menu-item>
    <el-menu-item class="el-icon-info"> 关于我</el-menu-item>
    <el-menu-item>
      <el-input placeholder="请输入内容" suffix-icon="el-icon-search"></el-input>
    </el-menu-item>
  </el-menu>
</template>

<script>
export default {
  name: 'base-header',
  data() {
    return {
      
    }
  },
  components: {

  }
}
</script>
  
<style lang="scss" scoped>

  .blog{
    font-family: "Helvetica Neue",Helvetica,"PingFang SC","Hiragino Sans GB","Microsoft YaHei","微软雅黑",Arial,sans-serif;
    color: #00b5ad;
    padding: 0;
    margin: 0;
  }

</style>
