<template>
  <div>
    <div class="mob-nav">
      <img class="logo" src="~/assets/shared/logo.svg" alt="" />
      <img src="~/assets/shared/icon-hamburger.svg" alt="" />
    </div>
    <div class="main-nav mob-hide">
      <img class="logo" src="~/assets/shared/logo.svg" alt="" />
      <nav>
        <ul>
          <li>
            <nuxt-link class="active" to="/"><span>00</span> Home</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/destination"><span>01</span> Destination</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/crew"><span>02</span> Crew</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/technology"><span>03</span> Technology</nuxt-link>
          </li>
        </ul>
      </nav>
    </div>
  </div>
</template>

<script>
export default {};
</script>
