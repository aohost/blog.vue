<template>
  <div id="app">
    <a-layout>
      <a-layout-header>Header</a-layout-header>
      <a-layout-content>
        <p>主页</p>  
        <router-view/>
      </a-layout-content>
      <a-layout-footer>Footer</a-layout-footer>
    </a-layout>
  </div>
</template>

<style lang="less">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.ant-layout-header{
  background: #fff !important;
}
</style>
