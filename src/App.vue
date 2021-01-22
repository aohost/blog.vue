<template>
  <div id="app" v-cloak>
    <a-layout>
      <loading></loading>
      <layout-header></layout-header>
      <layout-body></layout-body>
      <layout-footer></layout-footer>
    </a-layout>
  </div>
</template>

<script>
import LayoutBody from '@/components/layout/layout-body.vue'
import Loading from './components/loading.vue'
import LayoutHeader from './components/layout/layout-header.vue'
import LayoutFooter from './components/layout/layout-footer.vue'
export default {
  name:'app',
  components: { Loading, LayoutHeader, LayoutBody, LayoutFooter },
  
}
</script>

<style lang="less">
  #app {
      font-size: 17px;
      color: #6f6f6f;
  }
</style>
