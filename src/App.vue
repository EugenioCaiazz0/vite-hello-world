<script >
export default {
  data() {
    return {
      title: ` HelloWorld `
    }
  }
}
</script>

<template>
  <div>
      <img src="/vite.svg" class="logo" alt="Vite logo" />
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
  </div>
  <HelloWorld msg="Vite + Vue" />
  <h1 class="title"> {{title}} </h1>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
.title {
  background-image: linear-gradient(to left, violet, indigo, blue, green, yellow, orange, red);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
</style>
