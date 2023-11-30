<template>
  <nav class="flex items-center justify-between max-w-7xl mx-auto py-4 px-4 md:px-0">
    <div class="logo flex items-center gap-3">
      <img src="/logo.png" alt="sai-property-logo" class=" h-12 md:h-20">
      <div class="">
        <h3 class="md:text-2xl text-amber-200">Sai Properties</h3>
        <h4 class="text-[9px] md:text-xs uppercase text-zinc-500">Shubham Multi Developers</h4>
      </div>
    </div>
    <div class="hidden md:flex items-center gap-5">
      <NuxtLink class="text-sm text-zinc-400" to="/">Home</NuxtLink>
      <NuxtLink class="text-sm text-zinc-400" to="/">Property</NuxtLink>
    </div>
    <div class="hidden md:flex items-center gap-4">
      <a href="#contact" class="bg-amber-200 px-5 py-2 rounded-full text-zinc-800 flex items-center gap-1">
        <PhosphorIconPhone size="22" />
        <span class="">Contact Us</span>
      </a>
    </div>
  </nav>
</template>

<script setup>

</script>

<style>

</style>