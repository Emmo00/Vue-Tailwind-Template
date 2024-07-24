<script setup>
import GetStartedButton from '@/components/buttons/GetStartedButton.vue';

</script>

<template>
  <div class="flex flex-col items-center justify-center min-h-dvh">
    <div class="space-y-4 text-center">
      <h1 class="text-3xl font-bold tracking-tighter sm:text-4xl md:text-5xl">Welcome to our App</h1>
      <p class="max-w-[600px] text-muted-foreground md:text-xl">
        Discover a world of possibilities with our innovative app. Get started today and unlock a new level of
        productivity.
      </p>
      <GetStartedButton />
    </div>
  </div>
</template>