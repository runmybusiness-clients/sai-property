<template>
  <div class="md:min-h-[85vh] h-full">
    <div class="grid md:grid-cols-4 gap-6 max-w-7xl mx-auto py-12">
        <img 
          v-for="(image, index) in images"
          :key="index"
          :src="image"
          alt="sai-properties-map-location" 
          class="w-full object-cover md:h-[35vh] rounded-xl cursor-pointer"
          @click="onShow(index)"
        />
      </div>

      <vue-easy-lightbox
        :visible="visibleRef"
        :imgs="images"
        :index="indexRef"
        @hide="onHide"
      ></vue-easy-lightbox>
  </div>
</template>

<script setup>
  import VueEasyLightbox from 'vue-easy-lightbox'

  const visibleRef = ref(false)
  const indexRef = ref(null)

  const images = ref([
    '/projects/1.jpeg',
    '/projects/2.jpeg',
    '/projects/3.jpeg',
    '/projects/4.jpeg',
    '/projects/5.jpeg',
    '/projects/6.jpeg',
    '/projects/7.jpeg',
    '/projects/8.jpeg',
    '/projects/9.jpeg',
    '/projects/10.jpeg',
    '/projects/11.jpeg',
    '/projects/12.jpeg',
    '/projects/13.jpeg'
  ])

  const onShow = (index) => {
    visibleRef.value = true
    indexRef.value = index
  }
  const onHide = () => (visibleRef.value = false)
</script>

<style>

</style>