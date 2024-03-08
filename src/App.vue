<template>
  <div>
    <Student name="李四" sex="女" :age="18"></Student>
  </div>
</template>

<script>
// 引入School组件
import Student from './components/Student.vue'
export default {
    name: 'App',
    components: {
        Student
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