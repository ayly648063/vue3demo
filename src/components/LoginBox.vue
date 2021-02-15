<template>
    <div>登录</div>
  <el-row>
  <el-col :xs="20" :sm="17" :md="14" :lg="11" :xl="8"><div class="grid-content bg-purple"></div></el-col>
</el-row>
</template>

<style lang="less" scoped>
 .el-row {
    margin-bottom: 20px;
    &:last-child {
      margin-bottom: 0;
    }
  }
  .el-col {
    border-radius: 4px;
    margin: auto;
  }
  .bg-purple-dark {
    background: #99a9bf;
  }
  .bg-purple {
    background: #d3dce6;
  }
  .bg-purple-light {
    background: #e5e9f2;
  }
  .grid-content {
    border-radius: 4px;
    min-height: 36px;
  }
  .row-bg {
    padding: 10px 0;
    background-color: #f9fafc;
  }
</style>