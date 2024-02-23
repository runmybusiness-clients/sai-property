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
    '/projects/pro3-1.jpeg',
    '/projects/pro3-2.jpeg',
    '/projects/pro3-3.jpeg',
    '/projects/pro3-4.jpeg',
    '/projects/pro3-5.jpeg',
    '/projects/pro3-6.jpeg',
    '/projects/pro3-7.jpeg',
    '/projects/pro3-8.jpeg',
  ])

  const onShow = (index) => {
    visibleRef.value = true
    indexRef.value = index
  }
  const onHide = () => (visibleRef.value = false)
</script>

<style>

</style>