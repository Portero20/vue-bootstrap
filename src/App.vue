<script setup>
  import NavbarBootstrap from './components/NavbarBootstrap.vue';
  import JumbotronBootstrap from './components/JumbotronBootstrap.vue';
  import CallToAction from './components/CallToAction.vue';
  import CardsBootstrap from './components/CardsBootstrap.vue';
  import Footer from './components/FooterBootstrap.vue';
</script>

<template>
  <header>
    <div class="wrapper">
      <NavbarBootstrap />
      <JumbotronBootstrap/>
      <CallToAction />
      <CardsBootstrap/>
      <Footer/>

    </div>
  </header>

  <main>
    <TheWelcome />
  </main>
</template>

<style scoped>

</style>
