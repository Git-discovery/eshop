<template>
<el-form :model="form">
  <el-form-item label="用户名">
      <el-input v-model="username" placeholder="用户名"></el-input>
  </el-form-item>
  <el-form-item label="密&nbsp;码">
<el-input v-model="password" placeholder="密码"></el-input>
  </el-form-item>
</el-form>
</el-form>
</template>

<script>
export default {
  name: "login",
  data() {
    return {};
  }
};
</script>

<style lang="" scoped>
</style>