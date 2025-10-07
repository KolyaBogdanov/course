<template>
    <div class="tools-banner">
        <div class="tools-banner_wrap">
            <Logo :isBlack="true" />
            <img src="/Frame.svg" alt="">
    </div>  
        <ToolsBannerTitle />
        <ToolsBannerCards />
    </div>
    
</template>

<script setup>
import Logo from '@/components/Header/Logo.vue';
import ToolsBannerTitle from './ToolsBannerTitle.vue';
import ToolsBannerCards from './ToolsBannerCards.vue';


</script>

<style>
.tools-banner {
    background-color: rgb(204, 204, 204); 
    padding: 45px 40px 45px 40px;  
}

.tools-banner_wrap {
    display: flex;
    justify-content: space-between;
}

@media (max-width: 768px) {
    .tools-banner {
        padding: 30px 20px;
    }
}

@media (max-width: 480px) {
    .tools-banner {
        padding: 20px 15px;
    }
}
</style>