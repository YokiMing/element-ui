<template>
<el-row>
  <el-col :span="6"><div class="grid-content"></div></el-col>
  <el-col :span="12">
  <collapse></collapse>
  </el-col>
</el-row>
</template>
<script>
import Collapse from './collapse.vue'
export default {
  components: {
    Collapse
  }
}
</script>
<style>
  .el-row {
    margin-bottom: 20px;
    &:last-child {
      margin-bottom: 0;
    }
  }
  .el-col {
    border-radius: 4px;
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
