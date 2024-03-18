<template>
  <div class="demo">
    <h2 class="atguigu">学校姓名: {{ name }}</h2>
    <h2>学校地址: {{ address }}</h2>
  </div>
</template>

<script>
export default {
  name: "School",
  data() {
    return {
      name: "尚硅谷atguigu",
      address: "北京",
    };
  },
};
</script>

<style scoped lang="less">
    .demo {
        background-color: skyblue;
        .atguigu {
            font-size: 40px;
        }
    }
</style>