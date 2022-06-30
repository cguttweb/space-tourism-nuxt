<template>
  <main class="crew-background commander">
    <h2>02 Meet your crew</h2>

    <img src="~/assets/crew/image-douglas-hurley.png" alt="Douglas Hurley" />

    <nav class="crew-nav">
      <ul>
        <li class="active"><nuxt-link to="#">Commander</nuxt-link></li>
        <li><nuxt-link to="/engineer">Engineer</nuxt-link></li>
        <li><nuxt-link to="/pilot">Pilot</nuxt-link></li>
      </ul>
    </nav>

    <h3>Commander</h3>
    <h1>Douglas Hurley</h1>

    <p>
      Douglas Gerald Hurley is an American engineer, former Marine Corps pilot and former
      NASA astronaut. He launched into space for the third time as commander of Crew
      Dragon Demo-2.
    </p>
  </main>
</template>

<script>
export default {};
</script>
