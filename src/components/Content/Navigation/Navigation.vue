<template>
    <div class="navigation">
        <div class="navigation_title"        
        >
            Engage your audience with exclusive content.
        </div>
        <div class="navigation_subtitle">
            From virtual classes and workshops to newsletters, podcasts, and video series, Member Areas help you build, harness, and monetize the power of your online community.
        </div>
        <NavigationCards />
    </div>
</template>

<script setup>

import NavigationCards from './NavigationCards.vue';

</script>

<style>

.navigation {
    display: flex;
    flex-direction: column;
    background-color: #60777C;
    font-size: 27px;
    line-height: 27px;
}

.navigation_title {
    padding: 79px 0 22px 0;
    font-size: 56px;
    line-height: 56px;
    text-align: center;
    width: 604px;
    margin: auto;
}

.navigation_subtitle {
    font-size: 22px;
    line-height: 27px;
    text-align: center;
    width: 635px;
    margin: auto;
}

@media (max-width: 1024px) {
    .navigation_title {
        font-size: 48px;
        line-height: 48px;
        width: 80%;
        max-width: 550px;
        padding: 60px 0 20px 0;
    }
    
    .navigation_subtitle {
        font-size: 20px;
        line-height: 25px;
        width: 80%;
        max-width: 600px;
    }
}

@media (max-width: 768px) {
    .navigation_title {
        font-size: 36px;
        line-height: 36px;
        width: 90%;
        max-width: 500px;
        padding: 50px 0 18px 0;
    }
    
    .navigation_subtitle {
        font-size: 18px;
        line-height: 22px;
        width: 90%;
        max-width: 550px;
    }
}

@media (max-width: 480px) {
    .navigation_title {
        font-size: 28px;
        line-height: 28px;
        width: 95%;
        padding: 40px 0 15px 0;
    }
    
    .navigation_subtitle {
        font-size: 16px;
        line-height: 20px;
        width: 95%;
    }
}

@media (max-width: 360px) {
    .navigation_title {
        font-size: 24px;
        line-height: 24px;
        padding: 30px 0 12px 0;
    }
    
    .navigation_subtitle {
        font-size: 15px;
        line-height: 19px;
    }
}

</style>