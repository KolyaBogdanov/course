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

@media (max-width: 1024px) {
    .header_buttons {
        gap: 30px;
    }
}

@media (max-width: 768px) {
    .header_buttons {
        gap: 20px;
    }
    
    .categories {
        font-size: 14px;
    }
}

@media (max-width: 600px) {
    .header_buttons {
        gap: 15px;
    }
}

@media (max-width: 480px) {
    .header_buttons {
        gap: 10px;
    }
    
    .categories {
        font-size: 13px;
    }
}

</style>