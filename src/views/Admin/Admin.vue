<template>
  <div>
    <h1>這裡是後台</h1>
    <div id="nav">
      <router-link to="/">返回首頁</router-link> |
      <router-link to="/admin/products">產品列表</router-link> |
      <router-link to="/admin/coupons">優惠券</router-link> |
      <router-link to="/admin/order">訂單列表</router-link> |
      <router-link to="/admin/image">圖片列表</router-link>
    </div>
    <router-view/>
  </div>
</template>
