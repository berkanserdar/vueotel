<template>
  <div class="home">
    <Carousel class="home__Carousel">
    </Carousel>
    <OverlayImage class="home__OverlayImage">
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
.home__Carousel {
  margin-bottom: 50px;
}
.home__OverlayImage {
  margin-bottom: 50px;
}
</style>