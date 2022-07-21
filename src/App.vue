<template>
  <div>
    <header>
      <Title />
      <Hero />
    </header>
  </div>
</template>

<script>
import Title from './components/Title.vue';
import Hero from './components/Hero.vue';

export default {
  name: 'App',
  components: {
    Title,
    Hero,
  }
}
</script>

<style lang="scss">
* {
  margin: 0 auto;
  padding: 0;
  box-sizing: border-box;
}

body {
  height: 100vh;
  text-align: center;
  font-family: sans-serif;
}

header {
  background-image: radial-gradient(white 10%, red 40%, cornflowerblue);
  box-shadow: 2px 2px 5px gray;
}
</style>