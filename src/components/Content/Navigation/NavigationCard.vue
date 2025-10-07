<template>
    <div  
        v-for="item in navigations" 
        :key="item.id" class="card"
        :class="
        { 
            'card--white': item.isWhite,
            'card--reverse': item.reverse,
        }"
    >
        <div 
            class="card_description" 
            
        >
            <div class="card-description__title" 
            :class="{ 'card-description__title--black': item.blackTxt }" >
                {{ item.title }}
            </div>
            <div class="card_description__subtitle" 
            :class="{ 'card_description__subtitle--black': item.blackTxt }">
                {{ item.subtitle }}
            </div>
        </div>
        <div  class="card-wrapp__img">
            <img class="card__img" :src="item.src" alt="" >
        </div>
    </div>
</template>

<script setup>

import { ref } from 'vue'

const navigations = ref([
          {
            id: 1,
            src: '/NavigationOne.svg',
            title: 'Promote premium content.',
            subtitle: 'Whether you’re a chef selling recipes and cooking videos or a financial planner sharing newsletters and podcasts, Squarespace has the tools you need to protect and share your content.',
            isWhite: false,
            blackTxt: false,
            reverse: false,
          },
          {
            id: 2,
            src: '/NavigationTwo.svg',
            title: 'Share online classes.',
            subtitle: 'From virtual yoga classes to writing workshops, digital networking events to 1:1 coaching, our platform helps creators educate and inspire members.',
            isWhite: false,
            blackTxt: false,
            reverse: true,
          },
          {
            id: 3,
            src: '/NavigationThree.svg',
            title: 'Build a community.',
            subtitle: 'Help members connect with one another through virtual events, email updates, shared event calendars, and group workshops.',
            isWhite: false,
            blackTxt: false,
            reverse: false,
          },
          {
            id: 4,
            src: '/NavigationFour.svg',
            title: 'Integrate your newsletter.',
            subtitle: 'Member areas connect with Squarespace Email Campaigns. So you can manage lists and send newsletters all from the same place.',
            isWhite: false,
            blackTxt: false,
            reverse: true,
          },
          {
            id: 5,
            src: '/NavigationFour.svg',
            title: 'Protect your content.',
            subtitle: 'Other platforms allow users to bypass paywalls. Our tools ensure a seamless and secure member experience.',
            isWhite: true,
            blackTxt: true,
            reverse: true,
          },
          {
            id: 6,
            src: '/NavigationFour.svg',
            title: 'Protect your content.',
            subtitle: 'Other platforms allow users to bypass paywalls. Our tools ensure a seamless and secure member experience.',
            isWhite: false,
            blackTxt: false,
            reverse: false,
          }
        ])

</script >

<style scoped>

.card--reverse{
    flex-direction: row-reverse; 
}
.card--white {
    background-color: white;
    padding: 120px 40px !important;
}

.card-description__title--black {
    color: black;
}

.card_description__subtitle--black {
    color: black;
}

.card {
    display: flex;
    justify-content: space-between;
    padding: 0 40px 120px 40px;
    align-items: center;
}

.card-description{
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.card-description__title {
    font-size: 40px;
    line-height: 40px;
    padding-bottom: 40px;
}

.card_description__subtitle{
    font-size: 22px;
    line-height: 27px;
    width: 515px;
}

.card-wrapp__img {
    flex: 1;
    max-width: 50%; 
    min-width: 300px; 
}

.card__img {
    width: 100%;
    height: auto;
    object-fit: contain; 
}

@media (max-width: 768px) {
    .card {
        flex-direction: column !important; 
        text-align: center;
        padding: 0 20px 60px 20px;
    }
    
    .card-wrapp__img {
        max-width: 100%;
        min-width: auto;
    }
    
    .card_description__subtitle {
        width: 100%;
    }
}


</style>