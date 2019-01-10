<template>
    <div class="global-background">
        <div class="background-image"></div>
    </div>
</template>
<script>
export default {
    name:'background',

}
</script>
<style lang="scss" scoped>
    .global-background {
        position: fixed;
        width: 100%;
        height: 100%;
        top: 0;
        left: 0;
        z-index: -1;
        background-color: green;

        > .background-image {
        position: absolute;
        width: 100%;
        height: 100%;
        opacity: .3;
        background: url('../assets/img/background.png');
        }
    }
</style>


