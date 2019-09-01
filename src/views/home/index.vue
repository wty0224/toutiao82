<template>
  <el-container>
    <el-aside>
      <layout-left></layout-left>
    </el-aside>
    <el-container>
      <el-header>
        <layout-header></layout-header>
      </el-header>
      <el-main>main</el-main>
    </el-container>
  </el-container>
</template>

<script>
import layoutLeft from '../../components/home/layout-left'
import layoutHeader from '../../components/home/layout-header'

export default {
  components: {
    'layout-left': layoutLeft,
    'layout-header': layoutHeader

  }
}
</script>

<style >

</style>
