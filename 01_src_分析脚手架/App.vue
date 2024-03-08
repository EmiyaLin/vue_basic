<template>
    <div>
        <img src="./assets/logo.png" alt="logo">
        <SchoolName></SchoolName>
        <Studnet></Studnet>
    </div>
</template>

<script>
import SchoolName from './components/School.vue'
import Studnet from './components/Student.vue'

export default {
    name: 'App',
    components: {
        SchoolName,
        Studnet
    }
};
</script>

<style>
</style>