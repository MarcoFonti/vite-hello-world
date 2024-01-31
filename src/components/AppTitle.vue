<!-- JS -->
<script>
export default{
  name: 'AppHeader',
  data: () => ({
    paragraph: 'La mia prima app con Vite!'
  })
};
</script>

<!-- HTML -->
<template>
  <header>
    <p>"{{paragraph}}"</p>
  </header>
</template>

<!-- CSS -->
<style>
p {
    color: #a52a2a;
}
</style>