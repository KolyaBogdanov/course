<template>
    <div class="member-hero">
        <div class="membership-banner__title">
            <div class="member-hero__subtitle">sell online</div>
            <div class="member-hero__subtitle">member areas</div>
        </div>
        <div class="member-hero__accent">Create members‑only content.</div>
        <div class="member-hero__description">Monetize your content with Member Areas. Add paid areas to an existing Squarespace site or build a new one with our award-winning templates.</div>
        <HeaderBtn />
    </div>

</template>

<script setup>

import HeaderBtn from '@/components/Header/HeaderBtn.vue';

</script>

<style >
.member-hero {
    padding: 200px 0 0 40px;
    width: 540px;

    
}

.membership-banner__title{
    display: flex;
    justify-content: flex-start;
    gap: 50px;
} 

.member-hero__subtitle {
    text-transform: uppercase;
    font-size: 20px;
    line-height: 21px;
}
.member-hero__accent {
    font-size: 72px;
    line-height: 72px;
    padding-top: 20px;
}
.member-hero__description {
    padding-top: 25px;
    font-size: 22px;
    line-height: 27px;
    padding-bottom: 50px;
}
</style>