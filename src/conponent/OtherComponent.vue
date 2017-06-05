<template>
<el-row>
  <el-col :span="6"><div class="grid-content"></div></el-col>
  <el-col :span="12">
  <p>{{ greeting }} World !</p>
  <collapse></collapse>
  </el-col>
</el-row>
</template>
<script>
import Collapse from './collapse.vue'
export default {
  components: {
    Collapse
  },
  data: function() {
    return {
      greeting: 'Hello'
    }
  }
}
</script>