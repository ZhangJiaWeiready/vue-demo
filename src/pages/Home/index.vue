<template>
  <div class="content">
    {{name}}
  </div>
</template>
<script>
export default {
  // 当前页面的名称
  name: 'HOME',
  // 组件名
  components: {

  },
  /**
   * 过滤器
   * 一般里面放函数方法
   * 使用方法 {{ data | format }}  第一个值是参数 用 | 隔开 后面是filter的函数
   */
  filters: {
    // format(val) {
    //   return moment(val).format('YYYY-MM-DD HH:SS')
    // }
  },
  // 父组件传递来的值
  props: {
    // name: {
    //   type: String,
    //   default: 'none'
    // }
  },
  data () {
    return {
      name: 'Im 组件'
    }
  },
  computed: {

  },
  watch: {

  },
  // 生命周期
  created () {

  },
  mounted () {

  },
  // ^ 生命周期
  methods: {
    // methods 以 on开头
  }
}
</script>
<style  scope lang="less">
  .content {
    color: red;
  }
</style>
