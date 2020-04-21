<template>
  <div class="carousel_height">
    <el-carousel indicator-position="outside" height="500px">
        <el-carousel-item v-for="item in 4" :key="item">
            <!-- <h3>{{ item }}</h3> -->
        </el-carousel-item>
    </el-carousel>
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
.carousel_height{

}
.el-carousel__item h3 {
    color: #475669;
    font-size: 18px;
    opacity: 0.75;
    line-height: 300px;
    margin: 0;
}

.el-carousel__item:nth-child(2n) {
    background-image:url(../../assets/4.jpg);
    background-position:center;
    background-size:cover
}

.el-carousel__item:nth-child(2n+1) {
    background-image: url(../../assets/3.jpg);
    background-position:center;
    background-size:cover
}

</style>