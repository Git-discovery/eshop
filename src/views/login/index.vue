<template>

<el-form ref="form" :model="form" label-width="100px">
  <el-form-item label="用户名">
      <el-input v-model="username" placeholder="用户名"></el-input>
  </el-form-item>
  <el-form-item label="密码">
<el-input v-model="password" placeholder="密码"></el-input>
  </el-form-item>
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