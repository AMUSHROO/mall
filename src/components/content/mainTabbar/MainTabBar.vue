<template>
  <div>
    <tab-bar>
      <tab-bar-item path="/home" activeColor="#d4237a">
        <img slot="item-icon" src="~assets/img/tabbar/home.png" alt="">
        <img slot="item-icon-active" src="~assets/img/tabbar/home-avtive.png" alt="">
        <div slot="item-text">首页</div>
      </tab-bar-item>
      <tab-bar-item path="/classify" activeColor="#d4237a">
        <img slot="item-icon" src="~assets/img/tabbar/classify.png" alt="">
        <img slot="item-icon-active" src="~assets/img/tabbar/classify-active.png" alt="">
        <div slot="item-text">分类</div>
      </tab-bar-item>
      <tab-bar-item path="/cart" activeColor="#d4237a">
        <img slot="item-icon" src="~assets/img/tabbar/cart.png" alt="">
        <img slot="item-icon-active" src="~assets/img/tabbar/cart-active.png" alt="">
        <div slot="item-text">购物车</div>
      </tab-bar-item>
      <tab-bar-item path="/account" activeColor="#d4237a">
        <img slot="item-icon" src="~assets/img/tabbar/account.png" alt="">
        <img slot="item-icon-active" src="~assets/img/tabbar/account-active.png" alt="">
        <div slot="item-text">我的</div>
      </tab-bar-item>
    </tab-bar>
  </div>
</template>

<script>
  import TabBar from "components/common/tabbar/TabBar";
  import TabBarItem from "components/common/tabbar/TabBarItem";
  export default {
    name: "MainTabBar",
    components: {
      TabBar,
      TabBarItem
    }
  }
</script>

<style scoped>

</style>
