<template>
  <!-- Hero-area -->
  <section id="hero-area" class="hero-area">
    <img src="/images/hero_1.jpeg" alt="sai-property-hero-area" class="w-full object-cover h-[40vh] md:h-[85vh] shadow-xl rounded-3xl md:rounded-[100px]">
  </section>

  <section class="w-full md:py-20 py-6 px-3">
    <div class="grid md:grid-cols-3 gap-6 md:gap-12 max-w-7xl mx-auto">
      <div class="bg-gradient-to-r from-zinc-600 border-2 border-zinc-600 rounded-[40px] p-10">
        <h3 class="text-[3em] text-white">01</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
      </div>
      <div class="border-2 border-zinc-600 rounded-[40px] p-10">
        <h3 class="text-[3em] text-white">02</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
      </div>
      <div class="bg-amber-100 rounded-[40px] p-10">
        <h3 class="text-[3em] text-zinc-800">03</h3>
        <p class="text-zinc-800">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
      </div>
    </div>
  </section>

  <section class="w-full px-3">
    <div class="bg-gradient-to-r from-zinc-700 border-2 border-zinc-600 md:rounded-[100px] rounded-3xl p-4 md:p-10 max-w-7xl mx-auto flex flex-col md:flex-row items-center md:gap-12 gap-6">
      <div>
        <h3 class="text-md text-zinc-400 uppercase">Zirakpur</h3>
        <h3 class="text-[3em] text-white">Property Name</h3>
        <p class="text-zinc-400 text-md">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Sit praesentium delectus reiciendis enim fuga nihil deleniti, similique, omnis ducimus deserunt consequatur culpa earum placeat, accusamus tenetur quod sed dolorem! Eos?</p>
      </div>
      <img src="/images/image_1.jpeg" alt="" class="rounded-3xl md:rounded-[70px]">
    </div>
  </section>

  <!-- Properties -->
  <section class="pt-20 px-3">
    <div class="max-w-7xl mx-auto ">
      <div class="headings mb-4">
        <span class="text-md border border-zinc-600 rounded-2xl px-6 py-3 text-sm text-amber-200  uppercase">Properties</span>
        <h3 class="text-[2em] md:text-[3em] text-white mt-5">Featured Properties</h3>
      </div>
      <div class="grid md:grid-cols-3 gap-6">
        <div class="bg-gradient-to-r from-zinc-700 rounded-[20px] overflow-hidden items-center gap-12">
          <img src="/images/prop_1.jpeg" alt="sai-properties-map-location" class="w-full object-cover md:h-[40vh]">
          <div class="w-full flex items-center justify-between p-4">
            <div class="">
              <h2 class="text-xl">Property Name</h2>
              <h4 class="text-zinc-400 text-sm">VIP Road, Zirakpur</h4>
            </div>
            <button class="border border-amber-200 px-7 py-1.5 text-sm text-amber-200 rounded-lg">Explore</button>
          </div>
        </div>
        <div class="bg-gradient-to-r from-zinc-700 rounded-[20px] overflow-hidden items-center gap-12">
          <img src="/images/prop_2.jpeg" alt="sai-properties-map-location" class="w-full object-cover md:h-[40vh]">
          <div class="w-full flex items-center justify-between p-4">
            <div class="">
              <h2 class="text-xl">Property Two</h2>
              <h4 class="text-zinc-400 text-sm">VIP Road, Zirakpur</h4>
            </div>
            <button class="border border-amber-200 px-7 py-1.5 text-sm text-amber-200 rounded-lg">Explore</button>
          </div>
        </div>
        <div class="bg-gradient-to-r from-zinc-700 rounded-[20px] overflow-hidden items-center gap-12">
          <img src="/images/prop_3.jpeg" alt="sai-properties-map-location" class="w-full object-cover md:h-[40vh]">
          <div class="w-full flex items-center justify-between p-4">
            <div class="">
              <h2 class="text-xl">Property Three</h2>
              <h4 class="text-zinc-400 text-sm">VIP Road, Zirakpur</h4>
            </div>
            <button class="border border-amber-200 px-7 py-1.5 text-sm text-amber-200 rounded-lg">Explore</button>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Us -->
  <section class="pt-20 px-3" id="contact">
    <div class="max-w-7xl mx-auto ">
      <div class="headings mb-4">
        <span class="text-md border border-zinc-600 rounded-2xl px-6 py-3 text-sm text-amber-200  uppercase">Tired of Searching ?</span>
        <h3 class="text-[2em] md:text-[3em] text-white mt-5">Let experts do the work</h3>
      </div>
      <div class="flex flex-col md:flex-row bg-gradient-to-r from-zinc-700 border-2 border-zinc-600 rounded-3xl md:rounded-[100px] p-3 md:p-10 items-center gap-6 md:gap-12">
        <img src="/images/contact.jpeg" alt="sai-properties-map-location" class="rounded-3xl md:rounded-[70px] w-full h-full object-cover">
        <div class="w-full space-y-5">
          <input type="text" placeholder="Name" class="focus:outline-none w-full p-4 border rounded-xl bg-transparent border-zinc-600">
          <input type="email" placeholder="Email" class="focus:outline-none w-full p-4 border rounded-xl bg-transparent border-zinc-600">
          <input type="text" placeholder="Phone" class="focus:outline-none w-full p-4 border rounded-xl bg-transparent border-zinc-600">
          <button class="bg-amber-300 text-zinc-800 px-8 py-3 rounded-xl">Get help now</button>
        </div>
      </div>
    </div>
  </section>

  <!-- Map Location -->
  <section class="py-12 md:py-20 px-3">
    <div class="max-w-7xl mx-auto ">
      <div class="headings mb-4">
        <h3 class="text-md text-amber-200 uppercase">Shubham Multi Developers</h3>
        <h3 class="text-[2em] md:text-[4em] text-white">Sai Properties</h3>
      </div>
      <img src="/images/map.png" alt="sai-properties-map-location" class="rounded-xl md:rounded-[70px] w-full object-cover">
    </div>
  </section>

  <!-- Footer -->
  <footer class='p-4 bg-white md:flex md:items-center md:justify-between md:p-6 dark:bg-zinc-800 w-full'>
    <span class='hidden md:block text-sm text-zinc-500 sm:text-center dark:text-zinc-400'>© 2023 <a href='https://boltwind.ink/' class='hover:underline'>Sai Properties</a>. All Rights Reserved.</span>
    <div class='flex flex-wrap gap-5 items-center justify-between text-sm text-zinc-500 dark:text-zinc-400'>
      <a href='#' class='hover:underline'>About</a>
      <a href='#' class='hover:underline'>Privacy Policy</a>
      <a href='#' class='hover:underline'>Contact</a>
    </div>
  </footer>

</template>

<script setup>
  useSeoMeta({
    title: 'Sai Properties - Shubham multi developer',
    ogTitle: 'Sai Properties',
    description: 'Sai Properties - Shubham multi developer, best real estate agency in zirakpur, mohali.',
    ogDescription: 'Sai Properties - Shubham multi developer, best real estate agency in zirakpur, mohali.',
    ogImage: '/images/logo.png',
    twitterCard: '/images/logo.png',
  })
</script>

<style>

</style>