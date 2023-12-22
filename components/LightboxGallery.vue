<template>
  <div class="lightbox-gallery">
    <div v-if="showLightbox" class="lightbox-overlay" @click="closeLightbox">
      <div class="lightbox-content">
        <img :src="currentImage" alt="lightbox-image" />
        <button @click="prevImage" v-show="currentIndex > 0">Previous</button>
        <button @click="nextImage" v-show="currentIndex < images.length - 1">Next</button>
        <button @click="closeLightbox">Close</button>
      </div>
    </div>
    <div class="gallery">
      <img
        v-for="(image, index) in images"
        :key="index"
        :src="image"
        alt="gallery-image"
        @click="openLightbox(index)"
      />
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      showLightbox: false,
      currentIndex: 0,
      images: [
      'https://images.unsplash.com/photo-1703136681392-933106133b85',
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
      '/projects/13.jpeg',
      '/projects/14.jpeg',
      '/projects/15.jpeg',
      '/projects/16.jpeg',
      '/projects/17.jpeg',
      '/projects/18.jpeg',
      '/projects/19.jpeg',
      '/projects/20.jpeg',
      ],
    };
  },
  methods: {
    openLightbox(index) {
      this.currentIndex = index;
      this.showLightbox = true;
    },
    closeLightbox() {
      this.showLightbox = false;
    },
    nextImage() {
      if (this.currentIndex < this.images.length - 1) {
        this.currentIndex++;
      }
    },
    prevImage() {
      if (this.currentIndex > 0) {
        this.currentIndex--;
      }
    },
  },
};
</script>

<style scoped>
.lightbox-gallery {
  position: relative;
}

.lightbox-overlay {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.7);
  display: flex;
  align-items: center;
  justify-content: center;
}

.lightbox-content {
  position: relative;
}

.gallery {
  display: flex;
  flex-wrap: wrap;
}

.gallery img {
  width: 100px;
  height: 100px;
  margin: 5px;
  cursor: pointer;
}

</style>
