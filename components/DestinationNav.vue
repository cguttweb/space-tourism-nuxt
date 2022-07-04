<template>
  <div>
    <nav>
      <ul class="destination-nav">
        <li><nuxt-link to="/destination">Moon</nuxt-link></li>
        <li><nuxt-link to="/mars">Mars</nuxt-link></li>
        <li><nuxt-link to="/europa">Europa</nuxt-link></li>
        <li><nuxt-link to="/titan">Titan</nuxt-link></li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
ul {
  display: flex;
  justify-content: space-around;
  list-style: none;
  padding: 0 2rem;
}
</style>
