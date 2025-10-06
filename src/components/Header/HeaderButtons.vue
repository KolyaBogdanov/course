<template>
    <div className="header_buttons">
        <a href="" class='categories'>log in</a>
        <HeaderBtn />
    </div>
</template>

<script setup>
import HeaderBtn from './HeaderBtn.vue';


</script>

<style scoped>
.header_buttons {
    display: flex;
    justify-content: space-between;
    gap: 40px;
    text-decoration: none;
    color: black;
    align-items: center;
}

.categories {
    text-decoration: none;
    color: white;
    
}

</style>