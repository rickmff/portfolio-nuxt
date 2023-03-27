<template>
<NuxtLayout>
  <NuxtPage />
</NuxtLayout>
</template>

<script setup>
import { onMounted } from 'vue'
import { initFlowbite } from 'flowbite'

onMounted(() => {
    initFlowbite();
})
</script>