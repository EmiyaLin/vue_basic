<template>
  <!-- 组件的结构 -->
  <div class="demo">
    <h2>学校名称: {{ schoolName }}</h2>
    <h2>学校地址: {{ address }}</h2>
    <button @click="showName">点我提示学校名称</button>
  </div>
</template>

<script>
// 组件交互相关的代码
export default {
  name: "SchoolName",
  data() {
    return {
      schoolName: "尚硅谷",
      address: "北京",
    };
  },
  methods: {
    showName() {
      alert(this.schoolName);
    },
  },
};
</script>

<style scoped>
/* 组件的样式 */
.demo {
  background-color: blue;
}
</style>