<template>
  <nav>
    <ul class="crew-nav">
      <li><nuxt-link to="/crew">&nbsp;</nuxt-link></li>
      <li><nuxt-link to="/engineer">&nbsp;</nuxt-link></li>
      <li><nuxt-link to="/pilot">&nbsp;</nuxt-link></li>
    </ul>
  </nav>
</template>

<script>
export default {};
</script>

<style scoped>
ul {
  display: flex;
  justify-content: center;
  list-style: none;
}

li {
  /* background-color: #fff; */
  border: 1px solid #fff;
  border-radius: 50%;
  padding: 0.5rem 1rem;
  margin-right: 1rem;
}

a {
  text-decoration: none;
}
.active {
  border-bottom: none;
}
</style>
