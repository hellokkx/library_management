<template>
  <div style="text-align: center">
    <div style="margin-top: 150px;font-size: 80px;">
      404
    </div>
    <div style="font-size: 30px;">
      未找到页面
    </div>
    <el-button type="text" style="margin-top: 20px;font-size: 20px" @click="$router.push('/')">
      返回主页
    </el-button>
  </div>
</template>

<script>
export default {
  name: "404"
}
</script>

<style scoped>

</style>