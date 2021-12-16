<template>
  <div id="app">
    <div class="crx-content">
      <div id="down">
        <el-button type="success">测试</el-button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "App.vue",
  data() {
    return {

    }
  },
  created() {

  },
  methods: {
    // 复制成功时的回调函数
    onCopy(e) {
      this.msg = '复制成功'
      let that = this
      setTimeout(function () {
        that.msg = ''
      }, 1000)
    },
    // 复制失败时的回调函数
    onError(e) {
      this.msg = '复制失败'
      let that = this
      setTimeout(function () {
        that.msg = ''
      }, 1000)
    }
  }
}
</script>

<style scoped>
.crx-content div {
  position: fixed;
  top: 10%;
  left: 10px;
}

#open_background{
  top: 16%;
}

.crx-content {
  z-index: 9999;
  position: fixed;
  top: 10%;
  left: 10px;
}

</style>