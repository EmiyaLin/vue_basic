<template>
  <div>
    <Student></Student>
    <hr>
    <School></School>
  </div>
</template>

<script>
// 引入School组件
import Student from './components/Student.vue'
import School from './components/School.vue'

export default {
    name: 'App',
    components: {
        Student,
        School,
    },
    data() {
        return {
            msg: '欢迎学习Vue'
        }
    },
}
</script>

<style>
</style>