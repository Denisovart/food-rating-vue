<script>
  import { LinkButton } from "#components"
</script>

<template>
  <div class="h-[calc(100vh-140px)] w-screen bg-emerald-500 flex flex-col gap-20 items-center justify-center">
    <span class="text-3xl text-white">FOOD RANKING 0.0.21!</span>
    <LinkButton path="/about" label="Про нас" />
    <LinkButton path="/login" label="Войти" />
  </div>
</template>
