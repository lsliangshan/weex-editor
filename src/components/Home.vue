<template>
  <div class="home">
    <div class="headers_wrapper">
      <headers></headers>
    </div>
    <div class="contents_wrapper">
      <contents></contents>
    </div>
  </div>
</template>
<style scoped>
.home {
  width: 100%;
  height: 100%;
}
.headers_wrapper {
  width: 100%;
  height: 65px;
  overflow: hidden;
  border-bottom: 1px solid #eeeeee;
  box-sizing: border-box;
}
.contents_wrapper {
  width: 100%;
  height: calc(100% - 65px);
  background-color: #f5f5f5;
  overflow-y: auto;
}
</style>
<script>
export default {
  name: 'home',
  components: {
    Headers: () => import('./parts/Headers.vue'),
    Contents: () => import('./parts/Contents.vue')
  },
  data () {
    return {}
  }
}
</script>
