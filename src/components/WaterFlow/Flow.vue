<template>
  <div>
      <el-row :gutter="20">
			<el-col :span="6" >
				<div class="grid-content bg-purple">
					<img src="@/assets/1.jpg" style="width:100% "/>
					<div style="padding:25px 25px 0 25px">
						<h3 style="margin:10px 0">无版权限制的高清大图素材网站</h3>
						<div style="padding:20px 0">最近收集了一波免费图
                        片网站，相比于搜索出来的动不动就是版权限制，质量堪忧的图片，真是甩了好几条街了，分
                        享给大家，大家有需要自取吧，每个网站提供的图片类型
                        和质量都不一样，大家可以找合适自己的。</div>
					</div>
					<div style="height:30px;padding:0 25px 25px;">
						<ul style="list-style:none;margin: 0;padding:0;display:flex;justify-content:space-between;align-items:center;">
							<li>哇答西捏咩哟哇：精神小伙</li>
							<li style="">
								<a><img src="@/assets/smile.jpg" style="margin: 0 -5px;width: 34px;height:34px;display:inline-block;float:right;"/></a>
							</li>
						</ul>
					</div>
				</div>
			</el-col>
			<el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
			<el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
			<el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
		</el-row>
	</div>
  </div>
</template>
<script>

 
export default {
    //组件注册
    components: {
        
    },
    data() {
    return {
     
        };
    },
    //监听属性 类似于data概念
    computed: {},
    //监控data中的数据变化
    watch: {
       
    },
    //方法集合
    methods: {
      
    },
    //生命周期 - 创建完成（可以访问当前this实例）
    created() {

    },
    //生命周期 - 挂载完成（可以访问DOM元素）
    mounted() {

    },
    updated() {}, //生命周期 - 更新之后
    destroyed() {}, //生命周期 - 销毁完成
    activated() {}, //如果页面有keep-alive缓存功能，这个函数会触发
    
    }
</script>
<style  scoped>
.el-row {
    margin-bottom: 20px;
    &:last-child {
        margin-bottom: 0;
    }
}
.el-col {
    border-radius: 5px;
}
.bg-purple-dark {
    background: #ffffff;
}
.bg-purple {
    background: #ffffff;
}
.bg-purple-light {
    background: #e5e9f2;
}
.grid-content {
    box-shadow: 0px 0px 10px #ccc;
    border-radius: 4px;
    min-height: 36px;
}
.row-bg {
    padding: 10px 0;
    background-color: #f9fafc;
}
</style>