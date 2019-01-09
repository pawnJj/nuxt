<template>
<div>
    <div class="head">
        <div class="headList">
            <img class="logo" src="../../assets/img/logo.png" alt="">
            <span class="logo1"></span>
        </div>
    </div>
    <div class="headKong"></div>
</div>
</template>
<script>
export default {
    name:'',
    data(){
        return{

        }
    },
    mounted(){

    }
}
</script>
<style lang="scss" scoped>
    .head{
        position: fixed;
        width: 100%;
        height: 60px;
        @include top_bg($background-top2);
        @include top_border($border-top2);
        z-index: 99; 
        .headList{
            width: 1100px;
            margin: 0 auto;
            .logo{
                width: 50px;
                margin-top: 5px;
                float: left;
            }
            .logo1{
                float: left;
                // font-family: ;
                font-size: 28px;
            }
        }
    }
    
</style>


