<template>
  <!-- Hero-area -->
  <section id="hero-area" class="hero-area">
    <img src="/images/hero_1.jpeg" alt="sai-property-hero-area" class="w-full object-cover h-[40vh] md:h-[85vh] shadow-xl rounded-3xl md:rounded-[100px]">
  </section>

  <section class="w-full md:py-20 py-6 px-3">
    <div class="grid md:grid-cols-3 gap-6 md:gap-12 max-w-7xl mx-auto">
      <div class="bg-gradient-to-r from-zinc-600 to-zinc-400 border-2 border-zinc-600 rounded-[40px] p-10">
        <h3 class="text-[3em] text-white">01</h3>
        <h5 class="text-white font-bold text-xl">Company Vision and Mission</h5>
        <p class="text-zinc-100 text-sm mt-1">Provide a concise overview of your real estate company's vision and mission. Clearly articulate the goals and values that drive your business, emphasizing your commitment to client satisfaction, integrity, and excellence in real estate services.</p>
      </div>
      <div class="border-2 border-zinc-600 rounded-[40px] p-10">
        <h3 class="text-[3em] text-zinc-800">02</h3>
        <h5 class="text-zinc-800 font-bold text-xl">Expertise and Experience</h5>
        <p class="text-zinc-800 text-sm mt-1">Highlight the company's expertise and experience in the real estate industry. Briefly mention key milestones, years of operation, and any notable achievements. Showcase the depth of knowledge your team possesses, underscoring your ability to navigate the complexities of the market.</p>
      </div>
      <div class="border-2 border-amber-200 bg-amber-100 rounded-[40px] p-10">
        <h3 class="text-[3em] text-zinc-800">03</h3>
        <h5 class="text-zinc-800 font-bold text-xl">Client-Centric Approach</h5>
        <p class="text-zinc-800 mt-1 text-sm">Emphasize your company's dedication to a client-centric approach. Communicate how you prioritize understanding and fulfilling the unique needs of your clients, offering personalized solutions and building lasting relationships. Showcase testimonials or success stories that illustrate your commitment to delivering exceptional service and results.</p>
      </div>
    </div>
  </section>

  <section class="w-full px-3">
    <div class="bg-gradient-to-r from-zinc-700 to-zinc-100 border-2 border-zinc-600 md:rounded-[100px] rounded-3xl p-4 md:p-10 max-w-7xl mx-auto flex flex-col md:flex-row items-center md:gap-12 gap-6">
      <div>
        <h3 class="text-md text-zinc-400 uppercase">Zirakpur</h3>
        <h3 class="text-[3em] text-white">Property Name</h3>
        <p class="text-zinc-200 text-md">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Sit praesentium delectus reiciendis enim fuga nihil deleniti, similique, omnis ducimus deserunt consequatur culpa earum placeat, accusamus tenetur quod sed dolorem! Eos?</p>
      </div>
      <img src="/images/image_1.jpeg" alt="" class="rounded-3xl md:rounded-[70px] shadow-xl">
    </div>
  </section>

  <!-- Fetaured Properties -->
  <!-- <section class="pt-20 px-3">
    <div class="max-w-7xl mx-auto ">
      <div class="headings mb-4">
        <span class="text-md border border-zinc-600 rounded-2xl px-6 py-3 text-sm text-zinc-800  uppercase">Properties</span>
        <h3 class="text-[2em] md:text-[3em] text-zinc-800 mt-5">Featured Properties</h3>
      </div>
      <div class="grid md:grid-cols-3 gap-6">
        <div class="bg-gradient-to-l border from-zinc-100 rounded-[20px] overflow-hidden items-center gap-12">
          <img src="/images/prop_1.jpeg" alt="sai-properties-map-location" class="w-full object-cover md:h-[40vh]">
          <div class="w-full flex items-center justify-between p-4">
            <div class="">
              <h2 class="text-xl text-zinc-900">Property Name</h2>
              <h4 class="text-zinc-800 text-xs">VIP Road, Zirakpur</h4>
            </div>
            <button class="border border-zinc-700 px-7 py-1.5 text-sm text-zinc-700 rounded-lg">Explore</button>
          </div>
        </div>
        <div class="bg-gradient-to-l border from-zinc-100 rounded-[20px] overflow-hidden items-center gap-12">
          <img src="/images/prop_2.jpeg" alt="sai-properties-map-location" class="w-full object-cover md:h-[40vh]">
          <div class="w-full flex items-center justify-between p-4">
            <div class="">
              <h2 class="text-xl text-zinc-900">Property Name</h2>
              <h4 class="text-zinc-800 text-xs">VIP Road, Zirakpur</h4>
            </div>
            <button class="border border-zinc-700 px-7 py-1.5 text-sm text-zinc-700 rounded-lg">Explore</button>
          </div>
        </div>
        <div class="bg-gradient-to-l border from-zinc-100 rounded-[20px] overflow-hidden items-center gap-12">
          <img src="/images/prop_3.jpeg" alt="sai-properties-map-location" class="w-full object-cover md:h-[40vh]">
          <div class="w-full flex items-center justify-between p-4">
            <div class="">
              <h2 class="text-xl text-zinc-900">Property Name</h2>
              <h4 class="text-zinc-800 text-xs">VIP Road, Zirakpur</h4>
            </div>
            <button class="border border-zinc-700 px-7 py-1.5 text-sm text-zinc-700 rounded-lg">Explore</button>
          </div>
        </div>
      </div>
    </div>
  </section> -->

  <!-- Completed Project -->
  <section class="pt-20 px-3">
    <div class="max-w-7xl mx-auto">
      <div class="headings mb-4">
        <span class="text-md border border-zinc-600 rounded-2xl px-6 py-3 text-sm text-zinc-800  uppercase">Farm House In Morni</span>
        <div class="mt-5 flex flex-col md:flex-row w-full">
          <h3 class="text-[2em] md:text-[3em] text-zinc-800">Our Delievered Project</h3>
          <!-- <button class="border rounded-xl text-gray-500 hover:bg-gray-50 hover:text-gray-800 px-5 py-2 text-sm" @click="onShow">View all</button> -->
        </div>
      </div>
      
      <div class="grid md:grid-cols-2 gap-6">
        <!-- Project-1 -->
        <NuxtLink to="/delievered/farm-house" class="rounded-xl bg-white shadow p-1 overflow-hidden">
          <img src="/projects/1.jpeg" alt="" class="rounded-xl md:h-[50vh] w-full object-cover">
          <div class="p-2">
            <h1 class="text-xl">Farm House</h1>
            <p class="text-sm font-semibold text-yellow-800">Morni, Haryana</p>
          </div>
        </NuxtLink>
        <!-- Project-2 -->
        <NuxtLink to="/delievered/4bhk-independent" class="rounded-xl bg-white shadow p-1 overflow-hidden">
          <img src="/projects/inde-1.jpeg" alt="" class="rounded-xl md:h-[50vh] w-full object-cover">
          <div class="p-2">
            <h1 class="text-xl">Independent - 4 BHK House</h1>
            <p class="text-sm font-semibold text-yellow-800"></p>
          </div>
        </NuxtLink>
        <!-- Project-3 -->
        <NuxtLink to="/delievered/rental-proerty-1" class="rounded-xl bg-white shadow p-1 overflow-hidden">
          <img src="/projects/pro3-7.jpeg" alt="" class="rounded-xl md:h-[50vh] w-full object-cover">
        </NuxtLink>
        <!-- Project-4 -->
        <NuxtLink to="/delievered/rental-proerty-2" class="rounded-xl bg-white shadow p-1 overflow-hidden">
          <img src="/projects/pro4-6.jpeg" alt="" class="rounded-xl md:h-[50vh] w-full object-cover">
        </NuxtLink>
      </div>
    </div>
  </section>

  <!-- Happy Cutomers -->
  <section class="pt-20 px-3">
    <div class="max-w-7xl mx-auto">
      <div class="headings mb-4">
        <div class="flex flex-col md:flex-row w-full">
          <h3 class="text-[2em] md:text-[3em] text-zinc-800">Our Happy Customer's</h3>
        </div>
        <button class="my-5">
          <span class="text-md border border-zinc-600 rounded-2xl px-6 py-3 text-sm text-zinc-800  uppercase">Buyers</span>
        </button>
      </div>
      
      <div class="grid md:grid-cols-5 gap-6">
        <figure>
          <img src="/clients/buyers/1.jpeg" alt="" class="rounded-xl">
          <h4 class="text-center text-sm mt-2">Mr Pawan Kumar (Residential)</h4>
        </figure>
        <figure>
          <img src="/clients/buyers/2.jpeg" alt="" class="rounded-xl">
          <h4 class="text-center text-sm mt-2">Col Praveen thakur (Residential)</h4>
        </figure>
        <figure>
          <img src="/clients/buyers/3.jpeg" alt="" class="rounded-xl">
          <h4 class="text-center text-sm mt-2">Mr Ashish (Residential)</h4>
        </figure>
        <figure>
          <img src="/clients/buyers/4.jpeg" alt="" class="rounded-xl">
          <h4 class="text-center text-sm mt-2">Mr O P Sudha (Commercial)</h4>
        </figure>
        <figure>
          <img src="/clients/buyers/5.jpeg" alt="" class="rounded-xl">
          <h4 class="text-center text-sm mt-2">Mr Bramhjit Katyal (Commercial)</h4>
        </figure>
        <figure>
          <img src="/clients/buyers/6.jpeg" alt="" class="rounded-xl">
          <h4 class="text-center text-sm mt-2">Mr Ajay Sharma (Residential)</h4>
        </figure>
        <figure>
          <img src="/clients/buyers/7.jpeg" alt="" class="rounded-xl">
          <h4 class="text-center text-sm mt-2">Mr Ashmad Alok (Residential)</h4>
        </figure>
        <figure>
          <img src="/clients/buyers/8.jpeg" alt="" class="rounded-xl">
          <h4 class="text-center text-sm mt-2">Mr Navdeep Kohli (Residential)</h4>
        </figure>
        <figure>
          <img src="/clients/buyers/9.jpeg" alt="" class="rounded-xl">
          <h4 class="text-center text-sm mt-2">Mr Kamlesh (Residential)</h4>
        </figure>
        <figure>
          <img src="/clients/buyers/10.jpeg" alt="" class="rounded-xl">
          <h4 class="text-center text-sm mt-2">Col Sachit (Residential & Commercial)</h4>
        </figure>
        <figure>
          <img src="/clients/buyers/11.jpeg" alt="" class="rounded-xl">
          <h4 class="text-center text-sm mt-2">Dr Ashok Tamta (Residential)</h4>
        </figure>
      </div>

      <button class="my-5">
        <span class="text-md border border-zinc-600 rounded-2xl px-6 py-3 text-sm text-zinc-800  uppercase">Seller</span>
      </button>
      <div class="grid md:grid-cols-5 gap-6">
        <figure>
          <img src="/clients/seller/1.jpeg" alt="" class="rounded-xl">
          <h4 class="text-center text-sm mt-2">Mr Surinder (Residential)</h4>
        </figure>
        <figure>
          <img src="/clients/seller/2.jpeg" alt="" class="rounded-xl">
          <h4 class="text-center text-sm mt-2">Mr Manpal Singh (Commercial)</h4>
        </figure>
        <figure>
          <img src="/clients/seller/3.jpeg" alt="" class="rounded-xl">
          <h4 class="text-center text-sm mt-2">Mr Aashish (Residential)</h4>
        </figure>
        <figure>
          <img src="/clients/seller/4.jpeg" alt="" class="rounded-xl">
          <h4 class="text-center text-sm mt-2">Mr Jagdish Soni (Residential)</h4>
        </figure>

        <figure>
          <img src="/clients/seller/5.jpeg" alt="" class="rounded-xl">
          <h4 class="text-center text-sm mt-2">Mr Keshav Aggarwal ( Residential )</h4>
        </figure>
        <figure>
          <img src="/clients/seller/6.jpeg" alt="" class="rounded-xl">
          <h4 class="text-center text-sm mt-2">Mr Atul Ahuja ( Residential )</h4>
        </figure>
      </div>

    </div>
  </section>



  <!-- Contact Us -->
  <section class="pt-20 px-3" id="contact">
    <div class="max-w-7xl mx-auto ">
      <div class="headings mb-4">
        <span class="text-md border border-zinc-600 rounded-2xl px-6 py-3 text-sm text-zinc-800  uppercase">Tired of Searching ?</span>
        <h3 class="text-[2em] md:text-[3em] text-zinc-900 mt-5">Let experts do the work</h3>
      </div>
      <div class="flex flex-col md:flex-row border shadow rounded-3xl md:rounded-[100px] p-3 md:p-10 items-center gap-6 md:gap-12">
        <img src="/images/contact.jpeg" alt="sai-properties-map-location" class="rounded-3xl md:rounded-[70px] w-full h-full object-cover shadow-xl">
        <ContactForm />
      </div>
    </div>
  </section>

  <!-- Map Location -->
  <section class="py-12 md:py-20 px-3">
    <div class="max-w-7xl mx-auto ">
      <div class="headings mb-4">
        <h3 class="text-md text-zinc-800 uppercase">Shubham Multi Developers</h3>
        <h3 class="text-[2em] md:text-[4em] text-zinc-900">Sai Properties</h3>
      </div>
      <img src="/images/map.png" alt="sai-properties-map-location" class="rounded-xl md:rounded-[70px] w-full object-cover">
    </div>
  </section>

  <!-- Footer -->
  <footer class='p-4 bg-white md:flex md:items-center md:justify-between md:p-6 w-full border-t'>
    <span class='hidden md:block text-sm text-zinc-500 sm:text-center'>© 2023 <a href='https://boltwind.ink/' class='hover:underline'>Sai Properties</a>. All Rights Reserved.</span>
    <div class='flex flex-wrap gap-5 items-center justify-between text-sm text-zinc-500'>
      <NuxtLink to='/about' class='hover:underline'>About</NuxtLink>
      <NuxtLink to='/privacy' class='hover:underline'>Privacy Policy</NuxtLink>
    </div>
  </footer>

</template>

<script setup>
  definePageMeta({
    colorMode: 'light'
  })
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