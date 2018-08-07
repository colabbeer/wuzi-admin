<template>
  <div id="app">
    <el-container>
      <el-header>
        <mheader></mheader>
      </el-header>
      <el-main>Main</el-main>
    </el-container>
  </div>
</template>

<script>
  import Header from '@/components/Header'
export default {
  name: 'App',
  components: {
    'mheader': Header
  }
}
</script>

<style scoped>
.el-header {
  padding: 0;
  color: #fff;
  line-height: 80px;
}
</style>
