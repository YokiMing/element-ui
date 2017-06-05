<template>
<el-breadcrumb separator="/">
  <el-breadcrumb-item :to="{ path: '/' }">首页</el-breadcrumb-item>
  <el-breadcrumb-item :to="{ path: '/foo' }">标签一</el-breadcrumb-item>
  <el-breadcrumb-item :to="{ path: '/bar' }">标签二</el-breadcrumb-item>
  <el-breadcrumb-item :to="{ path: '/others' }">标签三</el-breadcrumb-item>
  <el-breadcrumb-item></el-breadcrumb-item>
</el-breadcrumb>
</template>