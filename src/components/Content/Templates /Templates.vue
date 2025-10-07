<template>
    <div class="templates">
        <div class="templates__title">
            Pick your starting point.
        </div>
        <div class="templates__description">
            Templates make it easy to get started. Just select a Member Areas template, then customize it to suit your needs.
        </div>
        <div class="templates__link">
            Browse Templates 
            <button class="templates__btn">→</button>
        </div>
        <div class="templates__carousel-container">
            <div class="templates__imgs">
                <img src="/TemplatesOne.svg" alt="">
                <img src="/TemplatesTwo.svg" alt="">
                <img src="/TemplatesOne.svg" alt="">
                <img src="/TemplatesTwo.svg" alt="">
            </div>
        </div>
        <div class="imgs__btns">
            
        </div>
    </div>
    
</template>

<script setup>

</script>

<style>

.templates {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    margin: 80px auto 80px auto;
    width: 640px;
    max-width: 90%; 
}

.templates__title{
    color: black;
    font-size: 56px;
    line-height: 56px;
    padding-bottom: 20px;
}

.templates__description {
    color: black;
    font-size: 22px;
    line-height: 26px;
    padding-bottom: 20px;
}

.templates__link{
    color: black;
    font-size: 22px;
    line-height: 21px;
    text-decoration: underline;
}

.templates__btn{
    font-size: 18px;
}

.templates__carousel-container {
    width: 100%;
    max-width: 100vw;
    margin: 0 auto;
    padding-top: 65px;
    overflow-x: auto;
    overflow-y: hidden;
    cursor: grab;
    -webkit-overflow-scrolling: touch;
}

.templates__carousel-container:active {
    cursor: grabbing;
}

.templates__carousel-container {
    scrollbar-width: none;
    -ms-overflow-style: none;
}

.templates__carousel-container::-webkit-scrollbar {
    display: none;
}

.templates__imgs {
    display: flex;
    gap: 40px;
    padding: 0 20px;
    width: max-content;
    margin-left: auto;
}

.templates__imgs img {
    flex: 0 0 auto;
    width: 280px;
    height: 180px;
    border-radius: 8px;
    object-fit: contain;
}

@media (max-width: 1024px) {
    .templates {
        width: 90%;
        margin: 60px auto 60px auto;
    }
    
    .templates__title {
        font-size: 48px;
        line-height: 48px;
    }
    
    .templates__description {
        font-size: 20px;
        line-height: 24px;
    }
    
    .templates__imgs img {
        width: 240px;
        height: 160px;
    }
}

@media (max-width: 768px) {
    .templates {
        width: 95%;
        margin: 40px auto 40px auto;
    }
    
    .templates__title {
        font-size: 36px;
        line-height: 36px;
        padding-bottom: 15px;
    }
    
    .templates__description {
        font-size: 18px;
        line-height: 22px;
        padding-bottom: 15px;
    }
    
    .templates__link {
        font-size: 18px;
    }
    
    .templates__carousel-container {
        padding-top: 40px;
    }
    
    .templates__imgs {
        gap: 20px;
        padding: 0 15px;
    }
    
    .templates__imgs img {
        width: 200px;
        height: 140px;
    }
}

@media (max-width: 480px) {
    .templates {
        margin: 30px auto 30px auto;
    }
    
    .templates__title {
        font-size: 28px;
        line-height: 28px;
    }
    
    .templates__description {
        font-size: 16px;
        line-height: 20px;
    }
    
    .templates__link {
        font-size: 16px;
    }
    
    .templates__imgs img {
        width: 160px;
        height: 120px;
    }
}
</style>