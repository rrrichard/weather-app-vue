<template>
  <div id="app">
    <main>
      <div class="search-box">
        <input type="text" class="search-bar" placeholder="Search..." />
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: "App",
  components: {},
  data() {
    return {
      api_key: "a5994bb9a09a7e631a3de6ef00177d0e",
    };
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: sans-seriff;
}

#app {
  background-image: url("./assets/cold.jpg");
  background-size: cover;
  background-position: bottom;
}

main {
  min-height: 100vh;
  padding: 25px;
}
</style>
