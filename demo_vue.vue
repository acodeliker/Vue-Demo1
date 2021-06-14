<!--
 * @Descripttion: 
 * @Author: voanit
 * @Date: 2021-04-05 13:27:58
 * @LastEditors: voanit
 * @LastEditTime: 2021-05-08 13:06:08
-->


<template>
  <fm-making-form ref="makingForm" upload preview generate-code generate-json clearable>
    <template slot="action">
    </template>
  </fm-making-form>
</template>

<script>
export default {
  data() {
    return {

    }
  },
  methods: {

  },
  components: {

  }
}
</script>

<style scoped>

</style>

<!-- 指定vue管理内容区域，需要通过vue展示的内容都要放到找个元素中  通常我们也把它叫做边界 数据只在边界内部解析-->
<div id="app">{{ msg }}</div>
​
<!-- 引入 vue.js -->
<script src="vue.js"></script>
​
<!-- 使用 vue -->
<script>
  var vm = new Vue({
    // el：提供一个在页面上已存在的 DOM 元素作为 Vue 实例的挂载目标
    el: '#app',
    // Vue 实例的数据对象，用于给 View 提供数据
    data: {
      msg: 'Hello Vue'
    }
  })
</script>