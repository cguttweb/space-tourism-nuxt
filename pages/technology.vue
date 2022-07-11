<template>
  <main class="technology-background">
    <section class="main-content">
      <h2>03 Space launch 101</h2>
      <img
        src="~/assets/technology/image-launch-vehicle-landscape.jpg"
        alt="launch vehicle"
      />

      <TechnologyNav />

      <h3>The terminology...</h3>
      <h1>Launch Vehicle</h1>
      <p class="body-text">
        A launch vehicle or carrier rocket is a rocket-propelled vehicle used to carry a
        payload from Earth's surface to space, usually to Earth orbit or beyond. Our WEB-X
        carrier rocket is the most powerful in operation. Standing 150 metres tall, it's
        quite an awe-inspiring sight on the launch pad!
      </p>
    </section>
  </main>
</template>

<script>
import TechnologyNav from "~/components/TechnologyNav.vue";
export default { components: { TechnologyNav } };
</script>
