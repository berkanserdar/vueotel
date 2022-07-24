<template>
<div id="app">
    <Navigation />
    
    <div class="router">
      <router-view/>
    </div>

    <Footer />
  </div>
</template>


<script>
import Navigation from '@/components/navbar/Navigation.vue'
import Footer from '@/components/footer/Footer.vue'

export default {
 name: "App",
 components: {
  Navigation,
  Footer,
 }
}
</script>

<style lang="scss">

* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: 'Times New Roman', Times, serif;
  font-weight: 400;
}
.router {
  padding-top: 75px;
}

.app {
  min-height: 100vh;
  position: relative;
  background-color: #f1f1f1;
}

.container {
  padding: 0 20px;
  max-width: 1140px;
  margin: 0 auto;
}
</style>
