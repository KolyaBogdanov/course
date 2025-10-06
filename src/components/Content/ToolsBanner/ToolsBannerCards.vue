<template>
    <div class="tools-banner__cards">
        <div 
            v-for="tool in tools" 
            :key="tool.id" 
            class="tools-banner__card"
        >
            <img :src="tool.src" :alt="tool.alt" class="tools-banner__img">
            <p class="tools-banner__card__title">
                {{ tool.title }}
            </p>
            <p class="tools-banner__card__description">
                {{ tool.description }}
            </p>
      </div>
    </div>
  </template>
  
  <script setup>
import { ref } from 'vue'

const tools = ref([
          {
            id: 1,
            src: '/ToolsOne.svg',
            alt: 'Share your expertise',
            title: 'Share your expertise.',
            description: 'Create classes, training, and packages for people of all skill levels and communities.'
          },
          {
            id: 2,
            src: '/ToolsTwo.svg',
            alt: 'Choose how you charge',
            title: 'Choose how you charge.',
            description: 'Charge a fee every week, month, or all at once. You can also make it completely free.'
          },
          {
            id: 3,
            src: '/ToolsThree.svg',
            alt: 'Everything in one place',
            title: 'Everything in one place.',
            description: 'Send emails, get insights, manage members, and choose where visitors sign up.'
          }
        ])
  

  </script>
  
  <style>
  .tools-banner__cards {
    display: flex;
    justify-content: space-between;
    align-items: stretch;
    padding-top: 50px;
    padding-left: 50px;
    padding-right: 50px;
    gap: 40px;
  }
  
  .tools-banner__card {
    display: flex;
    flex-direction: column;
    flex: 1;
  }
  
  .tools-banner__img {
    width: 100%;
    height: auto;
  }
  
  .tools-banner__card__title {
    font-size: 28px;
    line-height: 34px;
    color: black;
    padding-top: 20px;
  }
  
  .tools-banner__card__description {
    font-size: 18px;
    line-height: 21px;
    color: black;
  }
  </style>