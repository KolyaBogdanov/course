<template>
    <div class="tools-banner__title">
        All-in-one tools.
    </div>
    <div class="tools-banner__description">
        Get everything you need to create, share, and manage paid content with our versatile Member Areas.
    </div>
</template>

<script setup>

</script>

<style>
.tools-banner__title{
    color: black;
    text-align: center;
    font-size: 56px;
    line-height: 56px;
}

.tools-banner__description {
    color: black;
    margin: auto;
    text-align: center;
    font-size: 22px;
    line-height: 27px;
    width: 590px;
    padding-top: 20px;
}

@media (max-width: 1024px) {
    .tools-banner__title {
        font-size: 48px;
        line-height: 48px;
    }
    
    .tools-banner__description {
        font-size: 20px;
        line-height: 24px;
        width: 80%;
    }
}

@media (max-width: 768px) {
    .tools-banner__title {
        font-size: 36px;
        line-height: 36px;
    }
    
    .tools-banner__description {
        font-size: 18px;
        line-height: 22px;
        width: 90%;
        padding-top: 15px;
    }
}

@media (max-width: 480px) {
    .tools-banner__title {
        font-size: 28px;
        line-height: 28px;
    }
    
    .tools-banner__description {
        font-size: 16px;
        line-height: 20px;
        width: 95%;
    }
}
</style>