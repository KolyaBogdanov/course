<template>
    <div class="header_categories">
        <a 
            v-for="category in categories" 
            :key="category.id"
            :href="category.link" 
            class="categories"
        >
            {{ category.name }}
        </a>
    </div>
</template>

<script setup>
import { ref } from 'vue'

const categories = ref([
    { id: 1, name: 'products', link: '/products' },
    { id: 2, name: 'templates', link: '/templates' },
    { id: 3, name: 'resources', link: '/resources' }
])
</script>

<style scoped>
.header_categories {
    display: flex;
    justify-content: space-between;
    gap: 56px;
}

.categories {
    text-decoration: none;
    color: white;
}
</style>