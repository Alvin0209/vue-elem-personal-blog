<template>
<div class="f-footer">
	<el-main class="main">
		<el-row>
			<!-- <el-col :span="8" class="item-col">
				<div class="title">常用工具</div>
				<div class="item"><a href="#" class="out-link">aaa</a></div>
				<div class="item"><a href="#" class="out-link">aa</a></div>
			</el-col> -->
			<el-col :span="8" class="item-col">
				<div class="title">{{$t('footer.expressLane')}}</div>
				<div class=""><a href="#" class="out-link">{{$t('footer.gitee')}}</a></div>
				<div class=""><a href="#" class="out-link">CSDN</a></div>
				<div class=""><a href="#" class="out-link">{{$t('footer.admin')}}</a></div>
			</el-col>
			<el-col :span="8" class="item-col weside">
				<div class="item">
					<!-- <i class="el-icon-caret-right"></i> -->
				
				</div>
				<!-- <div class="item">
					<i class="el-icon-caret-right"></i>
					fengziy@aliyun.com
				</div> -->
				<!-- <div class="item">
					<i class="el-icon-caret-right"></i>
					© fengziy-博客 | 渝ICP备17015355
				</div> -->
			</el-col>
		</el-row>
	</el-main>
</div>
</template>

<script>
export default {
  name: 'footer'
}
</script>

<style scoped>
.f-footer{
	padding: 20px;
	text-align: center;
	color: #fff;
	background-color: #555;
}
.main{
	width: 70%;
	margin: 0 auto;
	color: #ccc;
}
.out-link{
	text-decoration: none;
	color: #ccc;
}
.out-link:hover{
	color: #ffffff;
}
.item-col{
	text-align: left;
}
.item-col.weside{
	font-size: 14px;
}
.item-col .title{
	color: #ddd;
	margin-bottom: 10px;
}
.item span{
	margin-right: 5px;
}
</style>