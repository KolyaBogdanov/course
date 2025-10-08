<template>
    <div class="member-areas__list">
        <ol class="member-areas__items">
            <li 
            v-for="item in memberItems" 
            :key="item.id"
             class="member-areas__item">
             {{ item.text}}
            </li>
        </ol>
    </div>
</template>

<script setup>
import { ref } from 'vue';


const memberItems = ref([
    {
        id: 1,
        text: 'Create a website with Squarespace, and decide on a name for your member area.',
    },
    {
        id: 2,
        text: 'Add members-only content, from classes to newsletters, guides to videos.',
    },
    {
        id: 3,
        text: 'Customize your member area landing and sign-up page with details about what you offer.',
    },
    {
        id: 4,
        text: 'Connect your preferred processor so you can start receiving fees.',
    },
    {
        id: 5,
        text: 'Add a Member Areas subscription to your existing Squarespace website plan.',
    }
]);

</script>

<style>

.member-areas__list {
    display: flex;
    justify-content: start;
    flex: 1;
}

.member-areas__items {
    list-style-type: decimal-leading-zero;
    padding-left: 30px;
    font-size: 22px;
    line-height: 27px;
    color: white;
}

.member-areas__item {
    margin-bottom: 25px;
}

@media (max-width: 1024px) {
    .member-areas__items {
        font-size: 20px;
        line-height: 25px;
    }
    
    .member-areas__item {
        margin-bottom: 22px;
    }
}

@media (max-width: 768px) {
    .member-areas__items {
        font-size: 18px;
        line-height: 23px;
        padding-left: 25px;
    }
    
    .member-areas__item {
        margin-bottom: 20px;
    }
}

@media (max-width: 480px) {
    .member-areas__items {
        font-size: 16px;
        line-height: 21px;
        padding-left: 20px;
    }
    
    .member-areas__item {
        margin-bottom: 18px;
    }
}

@media (max-width: 360px) {
    .member-areas__items {
        font-size: 15px;
        line-height: 20px;
        padding-left: 18px;
    }
    
    .member-areas__item {
        margin-bottom: 16px;
    }
}

</style>