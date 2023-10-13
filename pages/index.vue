<template>
  <main>
    <h1 class="red">Home page</h1>
    <NuxtLink to="/fun">
      Galeri Fun |
      </NuxtLink>

    <NuxtLink to="/vacation">
      Vacation
      </NuxtLink>

  </main>
</template>


<script>
  export default {
    // page properties go here
  }
</script>

<style>
  .red {
    color: red;
  }
</style>
