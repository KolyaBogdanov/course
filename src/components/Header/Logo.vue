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
}

.header_logo .logo--black {
  filter: brightness(0) saturate(100%);
}
</style>