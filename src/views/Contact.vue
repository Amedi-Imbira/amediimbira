<script>
import NavBar from "../components/NavBar.vue";
import Footer from "@/components/Footer.vue";

export default {
  components: {
    NavBar,
    Footer,
  },
};
</script>

<template>
  <NavBar />
  <iframe
    src="https://docs.google.com/forms/d/e/1FAIpQLScGX4sQTofJSC8SvbK6kt2z_7HBlDtgIOu1tM8EbD4LXL0FJg/viewform?embedded=true"
    width="640"
    height="988"
    frameborder="0"
    marginheight="0"
    marginwidth="0"
    >Loading…</iframe
  >
</template>

<style scoped>
iframe {
  width: 100%;
  overflow-x: hidden;
}
</style>
