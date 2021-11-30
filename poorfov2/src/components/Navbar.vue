<template>
  <nav class="grid grid-cols-2 gap-12">
    <div class="block inline-flex items-center">
      <img src="../assets/logos/Y.png" class="w-5/12 sm:w-3/12" />
    </div>
    <div class="flex justify-end items-center gap-5 mx-8 text-xl font-mono">
      <a class="hover:text-red-500">Home</a>
      <a class="hover:text-red-500">Contacto</a>
      <a class="hover:text-red-500">Proyectos</a>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
