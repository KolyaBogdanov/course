<template>
    <div class='membership_banner'>
        <MembershipBannerTitle />
    </div>
</template>

<script setup>
import MembershipBannerTitle from './MemberHero.vue';

</script>

<style>
.background_picture {
    object-fit: cover;
    height: 100vh;  
}

.membership_banner {
    background-image: url(../../public/Background.svg);
    background-repeat: no-repeat;
    background-position: center center;
    background-size: cover;
    background-attachment: fixed; /* Опционально */
    height: 100vh;
    width: 100%;
}
</style>