<template>

</template>

<script>
import HeaderTop from '../../components/HeaderTop/HeaderTop.vue'
import Swiper from 'swiper'
import 'swiper/dist/css/swiper.min.css'
export default {
    mounted () {
        // 创建一个Swiper实例对象
        new Swiper('.swiper-container', {
            loop: true, //循环轮播
            // 如果需要分页器
            pagination: {
            el: '.swiper-pagination',
            },
        })
    },
    components: {
        HeaderTop
    }
}
</script>

<style lang="stylus" rel="stylesheet/stylus">

</style>
