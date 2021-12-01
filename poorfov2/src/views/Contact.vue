<template>
  <div id="contact">
    <navbar />
    <div class="grid grid-cols-1 sm:grid-cols-6">
      <div class="flex flex-col items-center text-5xl col-start-2 col-span-3" id="titulo">
      
        <a href="https://fontmeme.com/es/fuente-de-super-mario/"
          ><img
            src="https://fontmeme.com/permalink/211201/f0c24097023ab2967939fd3f8a22772b.png"
            alt="fuente-de-super-mario"
            border="0"
        /></a>
          
            <img src="../assets/logos/qr-code.png" class=" lg:w-5/12 md:w-4/12 w-6/12 mt-6  flex items-center justify-content-center" />
          
      </div>

      <div class="">
        <lottie-player
          src="https://assets5.lottiefiles.com/packages/lf20_62cbhpxc.json"
          background="transparent"
          speed="0.6"
          style="width: 500px; height: 400px"
          loop
          autoplay
        ></lottie-player>
      </div>
    </div>
      <!--Footer-->
    <div class="grid mt-12 py-12">
      <div class="text-center font-mono font-bold text-black text-2xl">
        <h1>Yandry <span>&#169;</span> Villagómez</h1>
      </div>
      <div class="text-center font-mono font-bold text-black text-2xl">
        <h1>Madrid 2021</h1>
      </div>
    </div>
  </div>
  
</template>

<script>
import Navbar from "@/components/Navbar.vue";
import "@lottiefiles/lottie-player";

export default {
  name: "Contact",
  components: {
    Navbar,
  },
};
</script>
<style scoped>
@font-face {
  font-family: "Mario";
  src: local("Mario"),
    url(../assets/fonts/SuperMarioBros.ttf) format("truetype");
}

#titulo {
  font-family: "Mario";
}

.azul {
  color: #009cda;
}
</style>
