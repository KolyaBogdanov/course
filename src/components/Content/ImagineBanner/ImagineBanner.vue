<template>
    <div class="imagine-banner">
        <div class="imagine-banner__title">
            Imagine the possibilities.
        </div>
        <div class="imagine-banner__description">
            Member Areas give you the power to educate and inspire your audience.
        </div>
        <a class="imagine-banner__link">
            Watch the Video
        </a>    
    </div>
</template>

<script scoped>

</script>

<style>

.background_picture {
    object-fit: cover;
    height: 100vh;  
}

.imagine-banner {
    background-image: url(../../public/BackgroundImagine.svg);
    background-repeat: no-repeat;
    background-position: center center;
    background-size: cover;
    background-attachment: fixed; 
    display: flex;
    flex-direction: column;
    align-items: center;
    padding-top: 125px;
    text-align: center;
    gap: 20px;
}

.imagine-banner__title {
    font-size: 56px;
    line-height: 56px;
    width: 330px;
}

.imagine-banner__description {
    font-size: 22px;
    line-height: 27px;
    text-align: center;
    width: 500px;
}

.imagine-banner__link {
    font-size: 18px;
    line-height: 21px;
    text-decoration: underline;
    padding-bottom: 130px;
}

@media (max-width: 1024px) {
    .imagine-banner {
        padding-top: 100px;
        gap: 18px;
    }
    
    .imagine-banner__title {
        font-size: 48px;
        line-height: 48px;
        width: 300px;
    }
    
    .imagine-banner__description {
        font-size: 20px;
        line-height: 25px;
        width: 450px;
    }
    
    .imagine-banner__link {
        font-size: 17px;
        line-height: 20px;
        padding-bottom: 100px;
    }
}

@media (max-width: 768px) {
    .imagine-banner {
        padding-top: 80px;
        gap: 15px;
    }
    
    .imagine-banner__title {
        font-size: 36px;
        line-height: 36px;
        width: 250px;
    }
    
    .imagine-banner__description {
        font-size: 18px;
        line-height: 22px;
        width: 90%;
        max-width: 400px;
    }
    
    .imagine-banner__link {
        font-size: 16px;
        line-height: 19px;
        padding-bottom: 80px;
    }
    
    .background_picture {
        height: 80vh;
    }
}

@media (max-width: 480px) {
    .imagine-banner {
        padding-top: 60px;
        gap: 12px;
    }
    
    .imagine-banner__title {
        font-size: 28px;
        line-height: 28px;
        width: 200px;
    }
    
    .imagine-banner__description {
        font-size: 16px;
        line-height: 20px;
        width: 95%;
        max-width: 350px;
    }
    
    .imagine-banner__link {
        font-size: 15px;
        line-height: 18px;
        padding-bottom: 60px;
    }
    
    .background_picture {
        height: 70vh;
    }
}

@media (max-width: 360px) {
    .imagine-banner {
        padding-top: 50px;
        gap: 10px;
    }
    
    .imagine-banner__title {
        font-size: 24px;
        line-height: 24px;
        width: 180px;
    }
    
    .imagine-banner__description {
        font-size: 15px;
        line-height: 19px;
        width: 95%;
        max-width: 300px;
    }
    
    .imagine-banner__link {
        font-size: 14px;
        line-height: 17px;
        padding-bottom: 50px;
    }
    
    .background_picture {
        height: 60vh;
    }
}


@media (max-width: 768px) {
    .imagine-banner {
        background-attachment: scroll;
    }
}

@media (max-width: 768px) and (orientation: landscape) {
    .imagine-banner {
        padding-top: 60px;
        padding-bottom: 40px;
    }
    
    .imagine-banner__link {
        padding-bottom: 40px;
    }
}
</style>