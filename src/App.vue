<script setup>
  import hero from './components/hero-component.vue';
  import mainComponent from './components/main-component.vue';
  import testimonialsComponent from './components/testimonials-component.vue';
  import footerComponent from './components/footer-component.vue';
</script>

<template>
  <header>
  </header>
  <hero/>
  <mainComponent/>
  <testimonialsComponent/>
  <footerComponent/>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
