<script setup lang="ts">
  interface ILinkButtonProps {
    path: string,
    label: string
  }
  const { path, label } = defineProps<ILinkButtonProps>()
</script>

<template>
  <NuxtLink class="px-4 py-2 bg-white hover:scale-110 rounded-lg duration-150" :to=path>{{ label }}</NuxtLink>
</template>