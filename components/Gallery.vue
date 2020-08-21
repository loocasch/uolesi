<template>
  <div>
    <LightGallery
      :images="images"
      :index="index"
      :disable-scroll="true"
      @close="index = null"
    />
    <div class="row mt-5 justify-content-center card-box">
      <div
        v-for="(thumb, thumbIndex) in [
          require('~/assets/images/gallery/gallery1_thumb.jpg'),
          require('~/assets/images/gallery/gallery2_thumb.jpg'),
          require('~/assets/images/gallery/gallery3_thumb.jpg'),
          require('~/assets/images/gallery/gallery4_thumb.jpg'),
          require('~/assets/images/gallery/gallery6_thumb.jpg'),
          require('~/assets/images/gallery/gallery7_thumb.jpg'),
          require('~/assets/images/gallery/gallery8_thumb.jpg'),
          require('~/assets/images/gallery/gallery9_thumb.jpg'),
        ]"
        :key="thumbIndex"
        class="col-lg-3 col-md-4"
        @click="index = thumbIndex"
      >
        <div class="card p-3 mb-md-4 mb-3 text-default cursor-pointer">
          <img class="card-img-top" :src="thumb" />
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import { LightGallery } from 'vue-light-gallery'

export default {
  components: {
    LightGallery,
  },
  data() {
    return {
      images: [
        { url: require('~/assets/images/gallery/gallery1.jpeg') },
        { url: require('~/assets/images/gallery/gallery2.JPG') },
        { url: require('~/assets/images/gallery/gallery3.jpg') },
        { url: require('~/assets/images/gallery/gallery4.JPG') },
        { url: require('~/assets/images/gallery/gallery6.jpg') },
        { url: require('~/assets/images/gallery/gallery7.jpeg') },
        { url: require('~/assets/images/gallery/gallery8.jpeg') },
        { url: require('~/assets/images/gallery/gallery9.jpg') },
      ],
      index: null,
    }
  },
}
</script>
