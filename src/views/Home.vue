<script>
import NavBar from '../components/NavBar.vue'
import Hero from '../components/Hero.vue'
import Services from '@/components/Services.vue';
import Random from '@/components/Random.vue';
import WorkedWith from '@/components/WorkedWith.vue';
import Footer from '@/components/Footer.vue';
import Value from '@/components/Value.vue';

export default {
      components: {
            NavBar,
            Hero,
            Services,
            Random,
            Value,
            WorkedWith,
            Footer
      }
}
</script>

<template>
      <NavBar />
      <Hero />
      <Services />
      <Random />
      <Value />
      <Footer />

</template>