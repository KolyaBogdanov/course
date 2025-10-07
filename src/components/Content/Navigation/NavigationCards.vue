<template>
    <div class="navigation__cards">
        <NavigationCard />
    </div>   
</template>

<script setup>
import NavigationCard from './NavigationCard.vue';

</script>

<style>
.navigation__cards{
    padding-top: 120px;
}
@media (max-width: 1024px) {
    .navigation__cards{
        padding-top: 80px;
    }
}

@media (max-width: 768px) {
    .navigation__cards{
        padding-top: 60px;
    }
}

@media (max-width: 480px) {
    .navigation__cards{
        padding-top: 40px;
    }
}

@media (max-width: 360px) {
    .navigation__cards{
        padding-top: 30px;
    }
}

</style>