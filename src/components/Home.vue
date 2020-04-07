<template>

    <div>我是首页
  <router-link to="/test">去测试页面</router-link>
  <router-view></router-view>
    </div>
</template>

<script>
    export default {
        name: "Home"
    }
</script>

<style scoped>

</style>
