<template>
    <header class="header">
      <h1 class="title"> Dad Jokes</h1>
      <ul>
        <li>
          <nuxt-link to="/">Home</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/jokes">Jokes</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/aboutUs">About</nuxt-link>
        </li>
      </ul>
    </header>
</template>

<script>
    export default {
        name: "AppHeader"
    }
</script>

<style scoped>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 1rem;
  padding-bottom: 1rem;
  border-bottom: 1px dotted #ccc;
  border: #47494E
}

  .header .title {
    font-size: 3rem;
  }

  .header ul {
    display: flex;
  }

  .header a{
    display: inline-block;
    background: #47494E;
    color: #F5F5F5;
    padding: 0.3rem 1rem;
    margin-right: 0.5rem;
  }
</style>
