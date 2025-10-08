<template>

<div class="member-areas">
    <MemberAreasHeader />
    <MemberAreasList />
</div>

</template>

<script setup>

import MemberAreasHeader from './MemberAreasHeader.vue';
import MemberAreasList from './MemberAreasList.vue';

</script>

<style>

.member-areas {
    display: flex;
    background-color: black;
    padding: 80px 40px;
    gap: 180px;
}

@media (max-width: 1024px) {
    .member-areas {
        gap: 100px;
        padding: 60px 32px;
    }
}

@media (max-width: 768px) {
    .member-areas {
        flex-direction: column;
        gap: 50px;
        padding: 50px 24px;
    }
}

@media (max-width: 480px) {
    .member-areas {
        padding: 40px 16px;
        gap: 40px;
    }
}

@media (max-width: 360px) {
    .member-areas {
        padding: 32px 12px;
        gap: 32px;
    }
}
</style>