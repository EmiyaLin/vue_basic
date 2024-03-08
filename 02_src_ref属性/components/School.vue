<template>
  <div class="school">
    <div>学校名称: {{ SchoolName }}</div>
    <div>学校地址: {{ address }}</div>
  </div>
</template>

<script>
export default {
    name: 'School',
    data() {
        return {
            SchoolName: '尚硅谷',
            address: '北京'
        }
    }
};
</script>

<style>
    .school {
        background-color: gray;
    }
</style>