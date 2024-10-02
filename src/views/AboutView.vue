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
  <section class="section">
    <h3 class="header-two">About me</h3>
    <h1 class="subtitle">Sales Funnel Builder, Content Strategist, Writer</h1>
    <h4 class="header-one">
      The foundation of Eddie’s tech ethos is Open Source, as there is something
      in it for everyone; <br />no matter your role in the tech community you will
      find that you can become<br /> involved and learn from Open Source.
    </h4>
    <p>
      With clients ranging from UK Government departments, UK banks, global
      fintechs and startups, Eddie’s experiences range from <br />large corporate
      teams to small R&D teams. Eddie has had the opportunity to work with all
      disciplines in the tech industry; from <br /> developers, testers, UX/UI
      designers, technical writers, to product owners.
    </p>
    <br />
    <p>
      Having had the opportunity to learn from so many great colleagues, Eddie
      has always believed in giving back to <br /> the tech community with particular
      focus on creating and supporting opportunities for those wanting to start
      a career <br /> in tech, through diversity and inclusion programmes. This started
      out by mentoring and delivering workshops in <br />association with tech for
      good charities, to creating and building his own community, EddieHub.
    </p>
  </section>
  <Footer />
</template>
