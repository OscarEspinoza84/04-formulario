<template>
  <div class="container mt-3">
    <header/>


    <Formulario/>
  </div>
</template>

<script>
  import Header from "./components/Header.vue";
  import Formulario from "./components/Formulario.vue";

  export default {
      components:{
        Header,
        Formulario,
      },
  };
</script>