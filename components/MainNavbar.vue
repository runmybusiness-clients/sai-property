<template>
  <nav class="flex items-center justify-between max-w-7xl mx-auto py-2 px-4 md:px-0">
    <div class="logo flex items-center gap-3">
      <NuxtLink to="/" class="flex items-center gap-2">
        <img src="/logo.png" alt="sai-property-logo" class=" h-16 md:h-24">
        <div class="">
          <h3 class="md:text-2xl font-bold text-zinc-800 uppercase">Sai Properties</h3>
          <h4 class="text-[10px] md:text-[13px] uppercase text-zinc-700">Shubham Multi Developers</h4>
        </div>
      </NuxtLink>
    </div>
    <div class="hidden md:flex items-center gap-5">
      <NuxtLink class="text-sm text-zinc-700" to="/">Home</NuxtLink>
      <NuxtLink class="text-sm text-zinc-700" to="/about">About</NuxtLink>
    </div>
    <div class="hidden md:flex items-center gap-4">
      <a href="#contact" class="bg-zinc-700 px-6 py-3 rounded-full text-zinc-100 text-sm flex items-center gap-1">
        <PhosphorIconPhone size="20" />
        <span class="">Contact Us</span>
      </a>
    </div>
  </nav>
</template>

<script setup>

</script>

<style>

</style>