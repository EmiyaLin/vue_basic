<template>
  <div>
    <h2 @click="showName">学校姓名: {{ name }}</h2>
    <h2>学校地址: {{ address }}</h2>
  </div>
</template>

<script>
// 引入一个mixin
// import {mixin} from '../mixin'

export default {
    name: 'School',
    data() {
        return {
            name: '尚硅谷',
            address: '北京'
        }
    },
    // mixins: [mixin]
};
</script>

<style>
</style>