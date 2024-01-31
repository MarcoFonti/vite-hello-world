<!-- JS -->
<script>
// ! IMPORTO APPHEADER
import AppHeader from './components/AppTitle.vue'
// ! IMPORTO APPHERO
import AppHero from './components/AppHero.vue'

export default{
    name: 'MyApp',
    data: () => ({

    }),
    components: {
        AppHeader,
        AppHero
    }
};
</script>

<!-- HTML -->
<template>
<!-- APPHEADER -->
  <AppHeader/>
<!-- APPHERO -->
  <AppHero/>
</template>

<!-- CSS -->
<style>

</style>

