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

.navigation_subtitle{
    font-size: 22px;
    line-height: 27px;
    text-align: center;
    width: 635px;
    margin: auto;
}

</style>