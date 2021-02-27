<template>
  <div class="container">
    <AppHeader />
    <nuxt />
  </div>
</template>

<script>
  import AppHeader from "../components/AppHeader";
  export default {
      components: {AppHeader},
      comments: {
          AppHeader
      }
  }
</script>

<style>

  * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }

  body {
    font-family: Arial, Helvetica,sans-serif;
    font-size: 1rem;
    line-height: 1.6;
    background: white;
  }

  a {
    color: #666666;
    text-decoration: none;
  }

  ul {
    list-style: none;
  }

  li:active {
    color: #3b8070;
  }

  .container {
    max-width: 800px;
    margin: 2rem auto;
    overflow: hidden;
    padding: 1rem 2rem;
    background: #ffffff;
  }

</style>
