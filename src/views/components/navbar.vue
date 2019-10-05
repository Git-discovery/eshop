<template>
  <el-row :span="24">
    <el-col :span="18">
    <el-breadcrumb separator="|">
      <el-breadcrumb-item :to="{ path: '/home' }">首页</el-breadcrumb-item>
      <el-breadcrumb-item>
        <a href="/">男装</a>
      </el-breadcrumb-item>
      <el-breadcrumb-item>
        <a href="/">生鲜</a>
      </el-breadcrumb-item>
      <el-breadcrumb-item>
        <a href="/">食品</a>
      </el-breadcrumb-item>
      <el-breadcrumb-item>
        <a href="/">女装</a>
      </el-breadcrumb-item>
      <el-breadcrumb-item>
        <a href="/">鞋靴</a>
      </el-breadcrumb-item>
      <el-breadcrumb-item>
        <a href="/">箱包</a>
      </el-breadcrumb-item>
    </el-breadcrumb>
    </el-col>
  </el-row>
</template>

<script>
export default {
  name: "navbar",
  data() {
    return {};
  }
};
</script>

<style lang="" scoped>
.to-right {
  float: right;
}
</style>