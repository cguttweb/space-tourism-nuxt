<template>
  <nav>
    <ul class="crew-nav">
      <li><nuxt-link to="/crew">Crew</nuxt-link></li>
      <li><nuxt-link to="/specialist">Specialist</nuxt-link></li>
      <li><nuxt-link to="/engineer">Engineer</nuxt-link></li>
      <li><nuxt-link to="/pilot">Pilot</nuxt-link></li>
    </ul>
  </nav>
</template>

<script>
export default {};
</script>

<style scoped>
ul {
  display: flex;
  font-size: 30px;
  /* justify-content: space-around; */
  /* list-style: none; */
  padding: 0 2rem;
}

a {
  text-decoration: none;
}
.active {
  border-bottom: none;
}
</style>
