<template>
  <div class="home">
    <Carousel class="carousel">
    </Carousel>
    <OverlayImage class="overlayImage">
    </OverlayImage>
  </div>
</template>

<script>
// @ is an alias to /src
import Carousel from '@/components/pagecomponents/homepage/Carousel.vue';
import OverlayImage from '@/components/pagecomponents/homepage/OverlayImage.vue';

export default {
  name: 'Home',
  components: {
    Carousel : Carousel,
    OverlayImage : OverlayImage,
    }
}
</script>

<style scoped>
.carousel {
  margin-bottom: 50px;
}
.overlayImage {
  margin-bottom: 50px;
}
</style>