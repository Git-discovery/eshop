<template>
    <el-container>
    <el-breadcrumb separator="|">
      <el-breadcrumb-item :to="{ path: '/home' }">首页</el-breadcrumb-item>
      <el-breadcrumb-item>
        <a href="/">待定</a>
      </el-breadcrumb-item>
      <el-breadcrumb-item><a href="/login">登录</a></el-breadcrumb-item>
      <el-breadcrumb-item><a href="/regist">注册</a></el-breadcrumb-item>
    </el-breadcrumb>
  </el-container>
</template>

<script>
    export default {
        name: 'navbar',
        data() {
            return {
                
            }
        }
    }
</script>

<style lang="" scoped>
    
</style>