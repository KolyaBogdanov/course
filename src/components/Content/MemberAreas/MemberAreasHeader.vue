<template>
    <div class="member-areas__header">
        <h2 class="member-areas__title">
            <span class="member-areas__title-line">How to get started</span>
            <span class="member-areas__title-line">with Member Areas</span>
        </h2>
        <a href="#" class="member-areas__link">Get started →</a>
    </div>
</template>

<script setup>

</script>

<style>

.member-areas__header {
    flex: 1;
}

.member-areas__title {
    font-size: 56px;
    line-height: 56px;
    color: white;
    margin-bottom: 30px;
}

.member-areas__title-line {
    display: block;
}

.member-areas__link {
    text-transform: uppercase;
    font-size: 18px;
    line-height: 21px;
    text-decoration: underline !important;
    color: white;
}

@media (max-width: 1024px) {
    .member-areas__title {
        font-size: 48px;
        line-height: 48px;
    }
    
    .member-areas__link {
        font-size: 16px;
        line-height: 19px;
    }
}

@media (max-width: 768px) {
    .member-areas__title {
        font-size: 42px;
        line-height: 42px;
        margin-bottom: 25px;
    }
    
    .member-areas__link {
        font-size: 16px;
    }
}

@media (max-width: 480px) {
    .member-areas__title {
        font-size: 36px;
        line-height: 36px;
        margin-bottom: 20px;
    }
    
    .member-areas__link {
        font-size: 15px;
        line-height: 18px;
    }
}

@media (max-width: 360px) {
    .member-areas__title {
        font-size: 32px;
        line-height: 32px;
    }
    
    .member-areas__link {
        font-size: 14px;
        line-height: 17px;
    }
}

</style>