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
  padding-top: 73px;
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
::-webkit-scrollbar-track
{
	-webkit-box-shadow: inset 0 0 6px rgba(0,0,0,0.3);
	background-color: #F5F5F5;
	border-radius: 10px;
}

::-webkit-scrollbar
{
	width: 10px;
	background-color: #F5F5F5;
}

::-webkit-scrollbar-thumb
{
	border-radius: 10px;
	background-image: -webkit-gradient(linear,left bottom, left top,color-stop(0.22, rgb(247, 132, 132)),color-stop(0.44, rgb(228, 247, 132)),color-stop(0.66, rgb(132, 224, 247)),color-stop(0.72, rgb(73, 152, 189)),color-stop(0.86, rgb(28, 82, 148)));
}


</style>
