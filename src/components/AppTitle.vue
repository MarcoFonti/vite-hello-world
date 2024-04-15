<!-- JS -->
<script>


/* ESPORTAZIONE */
export default {


  /* NOME APP */
  name: 'AppHeader',


  /* DATI DI BASE */
  data: () => ({
    paragraph: 'La mia prima app con Vite!'
  })
};
</script>

<!-- HTML -->
<template>

  <!-- HEADER -->
  <header>
    <p>"{{ paragraph }}"</p>
  </header>

</template>


<!-- CSS -->
<style>
p {
  color: #a52a2a;
}
</style>