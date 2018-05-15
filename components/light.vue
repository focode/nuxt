<template>
  <lightbox :images="images"></lightbox>
</template>
<script>
import Vue from 'vue'
import lightbox from 'vlightbox';
Vue.use(lightbox);
export default {
    data: () => ({
    images: [
    {
        src: '/images/sample-1.jpg',
        caption: 'Image 1',
    },
    {
        src: '/images/sample-1.jpg',
    },
]
  })
}
</script>

