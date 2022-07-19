<template>
  <main class="technology-background">
    <section class="main-content technology">
      <h2>03 Space launch 101</h2>
      <img
        src="~/assets/technology/image-space-capsule-landscape.jpg"
        alt="space capsule"
      />

      <TechnologyNav />

      <h3 class="subheading-2">The terminology...</h3>
      <h1>Space capsule</h1>
      <p class="body-text">
        A space capsule is an often-crewed spacecraft that uses a blunt-body reentry
        capsule to reenter the Earth's atmosphere without wings. Our capsule is where
        you'll spend your time during the flight. It includes a space gym, cinema, and
        plenty of other activities to keep you entertained.
      </p>
    </section>
  </main>
</template>

<script>
import TechnologyNav from "~/components/TechnologyNav.vue";
export default { components: { TechnologyNav } };
</script>
