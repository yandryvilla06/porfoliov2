<template>
  <div class="home">
    <navbar id="nav" />
    <div class="grid grid-cols-1 lg:grid-cols-2 sm:grid-cols-1">
      <div class="mx-0 sm:mx-8">
        <img
          src="../assets/img/portada2.jpeg"
          class="w-full lg:rounded-full md:w-full lg:w-full sm:w-11/12"
        />
      </div>

      <div class="flex flex-wrap m-3 py-2">
        <svg viewBox="0 0 960 300">
          <symbol id="s-text">
            <text text-anchor="middle" x="50%" y="50%">Yandry Villa</text>

            <text text-anchor="middle" x="50%" y="100%">FullStack</text>
          </symbol>

          <g class="g-ants">
            <use xlink:href="#s-text" class="text-copy"></use>
            <use xlink:href="#s-text" class="text-copy"></use>
            <use xlink:href="#s-text" class="text-copy"></use>
            <use xlink:href="#s-text" class="text-copy"></use>
            <use xlink:href="#s-text" class="text-copy"></use>
          </g>
        </svg>
        <span class="text-2xl font-mono text-justify mt-2 m-6"
          >"Mi consejo es: nunca hagas mañana lo que puedes hacer hoy. La
          procrastinación es la ladrona del tiempo "<br />
          <p class="text-center mt-4">Charles Dickens</p>
        </span>
      </div>
    </div>

    <div
      class="grid grid-cols-5 lg:grid-cols-6 md:grid-cols-5 gap-2 mt-6 sm:mt-16"
    >
      <div class="col-start-2 col-span-3 sm:col-start-2">
        <div class="text-3xl font-extrabold text-end sm:text-5xl mb-5">
          <span
            class="bg-clip-text text-transparent bg-gradient-to-r from-red-700 to-yellow-500"
          >
            Acerca de mi
          </span>
        </div>
        <hr class="border-2 border-black" />
        <div>
          <p class="break-normal text-xl md:text-2xl font-serif text-gray-700">
            Holaa !! . Mi nombre es Yandry y soy un programador junior con
            muchas ganas de programar y crear cosas asombrosas. Mi amor a la
            programacion empezo cuando tenia 12 años desmontando y creando
            scripts en un ordenador con Windows Xp. Con los años me fue
            interesando más la programacion y la tecnologia asi que decidi
            graduarme en desarrollo de aplicaciones web.
          </p>
        </div>
      </div>
      <div
        class="lg:col-end-6 lg:col-span-1 md:col-start-2 md:col-span-3 col-start-2 col-span-3"
      >
        <img
          src="../assets/img/portada1.jpeg"
          class="w-full lg:w-8/12 sm:w-6/12"
        />
      </div>
    </div>

    <!-- LENGUAJES DE PROGRAMACION -->
    <div
      class="text-3xl font-extrabold text-center sm:text-5xl mb-5 mt-12 py-6"
    >
      <span
        class="bg-clip-text text-transparent bg-gradient-to-r from-red-700 to-yellow-500"
      >
        Lenguajes
      </span>
    </div>

    <div class="grid grid-cols-5 md:grid-cols-9 md:gri text-black gap-3 mb-8">
      <div class="col-start-2 md:col-start-4 col-span-1 k rounded-full">
        <img
          src="../assets/languages/css.svg"
          class="w-full lg:rounded-full md:w-full lg:w-full sm:w-11/12"
        />
      </div>
      <div class="col-start-3 md:col-start-5 col-span-1 rounded-full">
        <img
          src="../assets/languages/html.svg"
          class="w-full lg:rounded-full md:w-full lg:w-full sm:w-11/12"
        />
      </div>
      <div class="col-start-4 md:col-start-6 col-span-1 rounded-full">
        <img
          src="../assets/languages/javascript.png"
          class="w-full lg:rounded-full md:w-full lg:w-full sm:w-11/12"
        />
      </div>
      <div class="col-start-2 md:col-start-4 col-span-1 rounded-full">
        <img
          src="../assets/languages/linux.png"
          class="w-full lg:rounded-full md:w-full lg:w-full sm:w-11/12"
        />
      </div>
      <div class="col-start-3 md:col-start-5 col-span-1 rounded-full">
        <img
          src="../assets/languages/mysql.png"
          class="w-full lg:rounded-full md:w-full lg:w-full sm:w-11/12"
        />
      </div>
      <div class="col-start-4 md:col-start-6 col-span-1 rounded-full">
        <img
          src="../assets/languages/php.svg"
          class="w-full lg:rounded-full md:w-full lg:w-full sm:w-11/12"
        />
      </div>
      <div class="col-start-2 md:col-start-4 col-span-1 rounded-full">
        <img
          src="../assets/languages/python.png"
          class="w-full lg:rounded-full md:w-full lg:w-full sm:w-11/12"
        />
      </div>
      <div
        class="col-start-3 md:col-start-5 md:col-start-5 col-span-1 rounded-full"
      >
        <img
          src="../assets/languages/sql.png"
          class="w-full lg:rounded-full md:w-full lg:w-full sm:w-11/12"
        />
      </div>
      <div class="col-start-4 md:col-start-6 col-span-1 rounded-full">
        <img
          src="../assets/languages/java.png"
          class="w-full lg:rounded-full md:w-full lg:w-full sm:w-11/12"
        />
      </div>
    </div>
    <!-- Habilidades -->
    <div
      class="text-3xl mt-12 font-extrabold text-center sm:text-5xl sm:mb-5 sm:mt-16"
    >
      <span
        class="bg-clip-text text-transparent bg-gradient-to-r from-red-700 to-yellow-500"
      >
        Habilidades
      </span>
    </div>

    <div class="grid grid-cols-1 sm:grid-cols-2">
      <div>
        <lottie-player
          src="https://assets7.lottiefiles.com/private_files/lf30_kd6vmszk.json"
          background="transparent"
          speed="1"
          style="width: 1500; height: 500px"
          loop
          autoplay
        ></lottie-player>
      </div>
      <div
        class="flex flex-col items-center justify-center text-3xl sm:text-5xl mb-12 font-mono font-extrabold gap-5"
      >
        <div class="text-red-500"><h1>Autodidacta</h1></div>
        <div class="text-blue-600"><h1>Creativo</h1></div>
        <div class="text-gray-600"><h1>Trabajador</h1></div>
        <div class="text-yellow-300"><h1>Responsable</h1></div>
      </div>
    </div>
    <!-- Proyectos -->
    <div
      class="text-3xl mt-12 font-extrabold text-center sm:text-5xl sm:mb-5 sm:mt-16"
    >
      <span
        class="bg-clip-text text-transparent bg-gradient-to-r from-red-700 to-yellow-500"
      >
        Proyectos
      </span>
    </div>
     <div class="p-10">  
    <!--Card 1-->
    <div class="max-w-sm rounded overflow-hidden shadow-lg">
      <a href="http://yandryvillamo.com/#/">
      <img class="w-full" src="../assets/img/foodie.png" alt="Foodie">
      </a>
      <div class="px-6 py-4">
        <div class="font-bold text-xl mb-2">Foodie</div>
        <p class="text-gray-700 text-base">
          Es un aplicación de Delivery orientada al reparto de comida y gestión . Incorpora un CRM de ventas  para los restaurantes inscritos y un menu de los productos ofertadas en la app 
        </p>
      </div>
      <div class="px-6 pt-4 pb-2">
        <span class="inline-block bg-red-400 rounded-full px-3 py-1 text-sm font-semibold text-white-700 mr-2 mb-2">Php</span>
        <span class="inline-block bg-red-400 rounded-full px-3 py-1 text-sm font-semibold text-white-700 mr-2 mb-2">Html & Css</span>
        <span class="inline-block bg-red-400 rounded-full px-3 py-1 text-sm font-semibold text-white-700 mr-2 mb-2">Mysql</span>
      </div>
    </div>
  </div>



    <!--Footer-->
    <div class="grid">
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
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";
import "@lottiefiles/lottie-player";

export default {
  name: "Home",
  components: {
    Navbar,
  },
};
</script>

<style scoped>
@import url(https://fonts.googleapis.com/css?family=Montserrat);

html,
body {
  height: 100%;
  font-weight: 800;
}

body {
  font-family: Arial;
}

svg {
  display: block;
  font: 10.5em "Montserrat";
  width: 650px;
  height: 300px;
  margin: auto;
}

.text-copy {
  fill: none;
  stroke: white;
  stroke-dasharray: 6% 29%;
  stroke-width: 5px;
  stroke-dashoffset: 0%;
  animation: stroke-offset 5.5s infinite linear;
}

.text-copy:nth-child(1) {
  stroke: #4d163d;
  animation-delay: -1;
}

.text-copy:nth-child(2) {
  stroke: #840037;
  animation-delay: -2s;
}

.text-copy:nth-child(3) {
  stroke: #bd0034;
  animation-delay: -3s;
}

.text-copy:nth-child(4) {
  stroke: #bd0034;
  animation-delay: -4s;
}

.text-copy:nth-child(5) {
  stroke: #fdb731;
  animation-delay: -5s;
}

@keyframes stroke-offset {
  100% {
    stroke-dashoffset: -35%;
  }
}
</style>
