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
    height: 100vh;
    width: 100%;
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
}
</style>