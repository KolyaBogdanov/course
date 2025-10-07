<template>
<button class='header_btn'>
    get started
</button>
</template>

<script setup>

</script>

<style>

.header_btn {
    background-color: white;
    padding: 20px 30px;
    color: black;
    font-size: 14px;
    line-height: 14px;
    text-transform: uppercase;
    border: none;
    cursor: pointer;
    transition: all 0.3s ease;
}

@media (max-width: 1024px) {
    .header_btn {
        padding: 18px 25px;
        font-size: 13px;
    }
}

@media (max-width: 768px) {
    .header_btn {
        padding: 15px 20px;
        font-size: 12px;
    }
}

@media (max-width: 600px) {
    .header_btn {
        padding: 12px 18px;
        font-size: 11px;
    }
}

@media (max-width: 480px) {
    .header_btn {
        padding: 10px 15px;
        font-size: 10px;
    }
}

</style>