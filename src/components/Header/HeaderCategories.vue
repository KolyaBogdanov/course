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

@media (max-width: 1024px) {
    .header_categories {
        gap: 40px;
    }
}

@media (max-width: 768px) {
    .header_categories {
        gap: 30px;
    }
    
    .categories {
        font-size: 14px;
    }
}

@media (max-width: 600px) {
    .header_categories {
        order: 3;
        width: 100%;
        justify-content: center;
        gap: 20px;
        margin-top: 15px;
    }
}

@media (max-width: 480px) {
    .header_categories {
        gap: 15px;
    }
    
    .categories {
        font-size: 13px;
    }
}
</style>