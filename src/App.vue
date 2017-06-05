<template>
<div id="app">
<el-row>
  <el-col :span="24"><div class="grid-content"></div></el-col>
</el-row>
<el-row>
  <el-col :span="1"><div class="grid-content"></div></el-col>
  <el-col :span="11">
    <Breadcrumb></Breadcrumb>
  </el-col>
  <el-col :span="12">
  </el-col>
</el-row>
<!-- <el-row>
  <el-col :span="6"><div class="grid-content"></div></el-col>
  <el-col :span="12">
    <Carousel></Carousel>
  </el-col>
</el-row> -->
<router-view>
</router-view>
</div>
</template>
<style>
body {
  background: url("bg4.png");
}
</style>
<script>
import Breadcrumb from './conponent/breadcrumb.vue'
import Carousel from './conponent/carousel.vue'
export default {
  components: {
    Breadcrumb,
    Carousel
  }
}
</script>
