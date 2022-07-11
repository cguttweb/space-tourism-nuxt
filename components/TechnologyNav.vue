<template>
  <div>
    <nav>
      <ul class="technology-nav">
        <li><nuxt-link to="/technology">1</nuxt-link></li>
        <li><nuxt-link to="/spaceport">2</nuxt-link></li>
        <li><nuxt-link to="/capsule">3</nuxt-link></li>
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
  justify-content: center;
  list-style: none;
  padding: 0 2rem;
}

li {
  border: 1px solid #fff;
  border-radius: 50%;
  padding: 0.75rem 1rem;
}

a {
  color: #fff;
  text-decoration: none;
}
.active {
  border-bottom: 0;
}
</style>
