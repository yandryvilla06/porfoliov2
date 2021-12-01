<template>
  <div id="contact">
    <navbar />
    <div class="grid grid-cols-1 sm:grid-cols-6">
      <div class="text-5xl col-start-2 col-span-3" id="titulo">
        <!-- <a>¿</a><a class="azul">T</a><a>E</a> <a>G</a><a>U</a><a>S</a><a>T</a><a>A</a><a>R</a><a>I</a><a>A</a>
            
            <a>C</a><a>O</a><a>N</a><a>O</a><a>C</a><a>E</a><a>R</a><a>M</a><a>E</a><a>?</a>
            
             -->
        <a href="https://fontmeme.com/es/fuente-de-super-mario/"
          ><img
            src="https://fontmeme.com/permalink/211201/f0c24097023ab2967939fd3f8a22772b.png"
            alt="fuente-de-super-mario"
            border="0"
        /></a>
        <div class=" flex flex-col   sm:items-start items-center flex-wrapper">
        <div class="flex flex-row content-center justify-items-center">
          <div>
            <img src="https://img.icons8.com/stickers/200/000000/instagram-new--v1.png" class="w-full"/>
          </div>
        <div>
          <h1 class="mt-12 items-center content-center">Instagram</h1>
        </div>
          </div>
        <div><h1 class="mt-12">Instagram</h1></div>
        <div><h1 class="mt-12">Instagram</h1></div>

        </div>
        
      </div>

      <div class=" ">
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
