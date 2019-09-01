<template>
  <el-row type="flex" class="layout-header" justify="space-between">
    <el-col class="left" :span="6">
      <i class="el-icon-help icon"></i>
      <span>江苏传智播客教育科技股份有限公司</span>
    </el-col>
    <el-col class="right" :span="6">
      <img class="head-img" src="../../assets/img/avatar.jpg" alt />
      <el-dropdown trigger="click">
        <span class="el-dropdown-link">
          用户名
          <i class="el-icon-arrow-down el-icon--right"></i>
        </span>
        <el-dropdown-menu slot="dropdown">
          <el-dropdown-item icon="el-icon-plus">个人信息</el-dropdown-item>
          <el-dropdown-item icon="el-icon-circle-plus">git地址</el-dropdown-item>
          <el-dropdown-item icon="el-icon-circle-plus-outline">退出</el-dropdown-item>
        </el-dropdown-menu>
      </el-dropdown>
    </el-col>
  </el-row>
</template>

<script>
export default {}
</script>

<style lang="less" scopet>
.layout-header {
  padding: 8px 0;
  .left {
    .icon {
      font-size: 22px;
      margin-right: 3px;
    }
    display: flex;
    align-items: center;
  }
  .right {
    display: flex;
    align-items: center;
    .head-img {
      border-radius: 50%;
      margin-right: 5px;
      width: 40px;
      height: 40px;
    }
  }
}
</style>
