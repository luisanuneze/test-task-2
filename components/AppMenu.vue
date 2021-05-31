<template>
  <nav>
    <ul>
      <li>
        <nuxt-link exact to="/">Information</nuxt-link>
      </li>
      <li><nuxt-link to="/videoproduktion">Videoproduktion</nuxt-link></li>
    </ul>
  </nav>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

li {
  display: inline;
}

li a {
  color: white;
  padding-left: 2em;
}

.nuxt-link-active {
  color: #63b6b8;
}

ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #065488;
}
</style>
