<template>
<el-carousel :interval="4000" type="card" height="200px">
<el-carousel-item v-for="item in 6">
  <h3></h3>
</el-carousel-item>
</el-carousel>
</template>
<style>
.el-carousel__item h3 {
	color: #475669;
	font-size: 14px;
	opacity: 0.75;
	line-height: 200px;
	margin: 0;
}
.el-carousel__item {
	background-repeat: no-repeat;
	background-size: 100%;
}
.el-carousel__item:nth-child(2n+1) {
	background: url("../1.png");
}
.el-carousel__item:nth-child(2n) {
	background: url("../2.png");
}
.el-carousel__item:nth-child(3) {
	background: url("../3.png");
}
.el-carousel__item:nth-child(4) {
	background: url("../4.png");
}
.el-carousel__item:nth-child(5) {
	background: url("../5.png");
}
.el-carousel__item:nth-child(6) {
	background: url("../6.png");
}

</style>