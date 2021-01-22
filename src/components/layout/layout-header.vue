<template>
  <a-layout-header>
    <div class="site-logo">
      <img src="../../assets/WarGreymon.jpg" alt="鲸鱼" />
    </div>
    <div class="site-menus">
      <a-menu v-model="current" mode="horizontal">
        <a-menu-item key="home">
          <a-icon type="home" />首页
        </a-menu-item>
        <a-sub-menu>
          <span slot="title" class="submenu-title-wrapper">
            <a-icon type="menu" />文章
          </span>
            <a-menu-item key="setting:1">Option 1</a-menu-item>
            <a-menu-item key="setting:2">Option 2</a-menu-item>
        </a-sub-menu>
        <a-menu-item key="alipay">
          <a href="https://github.com/aohost" target="_blank" rel="noopener noreferrer">
            <a-icon type="github" />GitHub
          </a>
        </a-menu-item>
      </a-menu>
    </div>
  </a-layout-header>
</template>

<script>
export default {}
</script>

<style lang="less" scoped>
.ant-layout-header {
  background: #fff;
  display: flex;
  justify-content: space-between;
}

.site-logo {
  height: 100%;
  img {
    height: 80%;
  }
}

.site-menus {
  display: flex;
  height: 100%;
  align-items: center;
}
</style>
