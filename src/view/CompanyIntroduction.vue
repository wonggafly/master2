<template>
    <div id="CompanyIntroduction">
        <div class="banner container-fuild text-center">关于我们</div>
        <div class="container">
            <div class="row CompanyIntroduction-container">
                <div class="col-xs-12 col-sm-12 col-md-6 wow zoomIn">
                    <img class="img-responsive center-block" src="@/assets/img/rec.jpg">
                </div>
                <div class="col-xs-12 col-sm-12 col-md-6">
                    <h3>公司介绍</h3>
                    <p class=".text-justify">
                        广州掌动智能科技有限公司是数字化转型基础支撑软件核心技术提供商，以“赋能中国质量”为使命，旨在研发基础支撑软件“卡脖子“技术，在智能化诊断、IT反脆弱性、云可观测性等技术上弯道超车，打破发达国家垄断，为大型数字化系统提供集测试诊断、性能监控与故障演练三位一体的质量保障，降低系统在各种突发事件下发生拥塞、崩溃的可能性，为数字化系统稳定、健康、高质量运行保驾护航。
                    </p>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
import { WOW } from 'wowjs';
export default {
    name: 'CompanyIntroduction',
    data(){
        return{

        }
    },
    mounted(){
        var wow = new WOW();
        wow.init();
    }
}
</script>
<style scoped>
.banner{
    color: #fff;
    font-size: 30px;
    height: 150px;
    line-height: 150px;
    background-image: url('../assets/img/banner1.png');
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: scroll;
    background-position: center center;
}
.row{
    margin-right: 0;
    margin-left: 0;
}
.CompanyIntroduction-container{
    padding: 100px 0;
    color: #808080;
    transition: all ease 0.5s;
}
.CompanyIntroduction-container>div>p{
    font-size: 14px;
    line-height: 2.5rem;
}
@media screen and (max-width: 997px){
    .CompanyIntroduction-container{
    padding: 10px 0;
    color: #808080;
}
}
</style>

