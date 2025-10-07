<template>
    <div>
      <div class='header_logo'>
        <img class="logo" :class="{ 'logo--black': isBlack }" src="/Logo.svg" alt="Logo" />
      </div>
    </div>
</template>

<script setup>

defineProps({
  isBlack: {
    type: Boolean,
    default: false
  }
})
</script>

<style scoped>
.header_logo .logo {
  filter: brightness(0) saturate(100%) invert(1);
  transition: filter 0.3s ease;
  width: 100%;
  height: auto;
}

.header_logo .logo--black {
  filter: brightness(0) saturate(100%);
}

@media (max-width: 768px) {
    .header_logo {
        max-width: 120px;
    }
}

@media (max-width: 480px) {
    .header_logo {
        max-width: 100px;
    }
}
</style>