<script setup>

</script>

<template>

        <div class="menu">
            <div class="logo">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 48 48" width="50" height="50">
                <g data-name="3-Food equipment">
                <path d="M24 48a24 24 0 1 1 24-24 24.028 24.028 0 0 1-24 24zm0-46a22 22 0 1 0 22 22A22.025 22.025 0 0 0 24 2z"/>
                <path d="M12.412 37.765a17.975 17.975 0 0 1-2.126-25.412l1.524 1.294a15.976 15.976 0 0 0 1.89 22.588zM35.645 37.765l-1.29-1.53a15.975 15.975 0 0 0 1.892-22.588l1.524-1.294a17.975 17.975 0 0 1-2.126 25.412zM18 19a5.006 5.006 0 0 1-5-5V7h2v7a3 3 0 0 0 6 0V7h2v7a5.006 5.006 0 0 1-5 5z"/>
                <path d="M17 5h2v21h-2z"/>
                <path d="M18 43a3 3 0 0 1-3-3V28a3 3 0 0 1 6 0v12a3 3 0 0 1-3 3zm0-16a1 1 0 0 0-1 1v12a1 1 0 0 0 2 0V28a1 1 0 0 0-1-1zM29 18h2v8h-2z"/>
                <path d="M30 43a3 3 0 0 1-3-3V28a3 3 0 0 1 6 0v12a3 3 0 0 1-3 3zm0-16a1 1 0 0 0-1 1v12a1 1 0 0 0 2 0V28a1 1 0 0 0-1-1zM30 19c-2.8 0-5-3.075-5-7s2.2-7 5-7 5 3.075 5 7-2.2 7-5 7zm0-12c-1.626 0-3 2.29-3 5s1.374 5 3 5 3-2.29 3-5-1.374-5-3-5z"/>
    </g>
</svg>
            </div>
            <el-menu class="nav el-menu-vertical-demo">
        <el-menu-item index="1">
            <el-icon :size="24"><Food /></el-icon>
        </el-menu-item>

        <el-menu-item index="2">
            <el-icon :size="24"><Dish /></el-icon>
        </el-menu-item>

      </el-menu>
        </div>

</template>

<style lang="sass" scoped>
@import '@/assets/styles/index'

.menu 
    height: 100vh
    padding: 20px 5px 0
    border-right: 1px solid $border

.nav 
    border: none 

.logo
    padding: 0 5px 15px 
    border-bottom:  1px solid $border
</style>
