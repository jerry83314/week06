<template>
    <div>
        <h2>這是後台管理頁面</h2>
        <div id="nav">
            <router-link to="/">返回前台</router-link> |
            <router-link to="/admin/products">產品列表</router-link> |
            <router-link to="/admin/coupons">優惠券列表</router-link> |
            <router-link to="/admin/order">訂單列表</router-link> |
            <router-link to="/admin/images">圖片列表</router-link>
            <router-view></router-view>
        </div>
    </div>
</template>
