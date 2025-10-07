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
    padding: 200px 0 80px 40px;
    width: 540px;
    max-width: 90%; 
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

@media (max-width: 1024px) {
    .member-hero {
        padding: 100px 0 50px 30px;
        width: 480px;
    }
    
    .member-hero__accent {
        font-size: 60px;
        line-height: 60px;
    }
    
    .member-hero__description {
        font-size: 20px;
        line-height: 25px;
    }
    
    .membership-banner__title {
        gap: 40px;
    }
    
    .member-hero__subtitle {
        font-size: 18px;
        line-height: 19px;
    }
}

@media (max-width: 768px) {
    .member-hero {
        padding: 60px 20px 30px 20px;
        width: 100%;
        text-align: center;
    }
    
    .member-hero__accent {
        font-size: 48px;
        line-height: 48px;
        padding-top: 15px;
    }
    
    .member-hero__description {
        font-size: 18px;
        line-height: 22px;
        padding-top: 20px;
        padding-bottom: 40px;
    }
    
    .membership-banner__title {
        justify-content: center;
        gap: 30px;
    }
    
    .member-hero__subtitle {
        font-size: 16px;
        line-height: 17px;
    }
}

@media (max-width: 480px) {
    .member-hero {
        padding: 30px 15px 15px 15px;
    }
    
    .member-hero__accent {
        font-size: 36px;
        line-height: 36px;
        padding-top: 10px;
    }
    
    .member-hero__description {
        font-size: 16px;
        line-height: 20px;
        padding-top: 15px;
        padding-bottom: 30px;
    }
    
    .membership-banner__title {
        flex-direction: column;
        gap: 10px;
    }
    
    .member-hero__subtitle {
        font-size: 14px;
        line-height: 15px;
    }
}

@media (max-width: 360px) {
    .member-hero {
        padding: 20px 10px 10px 10px;
    }
    
    .member-hero__accent {
        font-size: 32px;
        line-height: 32px;
    }
    
    .member-hero__description {
        font-size: 15px;
        line-height: 19px;
    }
    
    .member-hero__subtitle {
        font-size: 13px;
        line-height: 14px;
    }
}
</style>