<template>
   <div class="header">
        <Logo />
        <HeaderCategories/>
        <HeaderButtons />
   </div>
</template>

<script setup>
import Logo from './Logo.vue';
import HeaderCategories from './HeaderCategories.vue';
import HeaderButtons from './HeaderButtons.vue';    

</script>

<style scoped>

.header {
    background-color: #000000;
    display: flex;
    justify-content: space-between;
    align-items: center;
    text-align: center;
    text-transform: uppercase;
    padding: 12px 40px;
    position: relative;
    z-index: 10;
       
}

</style>