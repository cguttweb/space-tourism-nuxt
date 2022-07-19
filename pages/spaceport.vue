<template>
  <main class="technology-background">
    <section class="main-content technology">
      <h2>03 Space launch 101</h2>
      <img src="~/assets/technology/image-spaceport-landscape.jpg" alt="space capsule" />

      <TechnologyNav />

      <h3 class="subheading-2">The terminology...</h3>
      <h1>Spaceport</h1>
      <p class="body-text">
        A spaceport or cosmodrome is a site for launching (or receiving) spacecraft, by
        analogy to the seaport for ships or airport for aircraft. Based in the famous Cape
        Canaveral, our spaceport is ideally situated to take advantage of the Earth’s
        rotation for launch.
      </p>
    </section>
  </main>
</template>

<script>
import TechnologyNav from "~/components/TechnologyNav.vue";
export default { components: { TechnologyNav } };
</script>
