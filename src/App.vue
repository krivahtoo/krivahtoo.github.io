<template>
  <div id="app">
    <TheHeader />
    <div class="circle1"></div>
    <div class="circle2"></div>
  </div>
</template>

<script>
import TheHeader from './components/TheHeader'

export default {
  name: 'App',
  components: {
    TheHeader,
  },
}
</script>

<style lang="scss">
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #41388f;
  font-family: 'Poppins', sans-serif;
  min-height: 100vh;
  background: linear-gradient(to right top, #28a991, #23a1b5);
  display: flex;
  align-items: center;
  justify-content: center;
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

h1 {
  color: #092344;
  font-weight: 600;
  font-size: 3rem;
  opacity: 0.8;
}
h2,
p {
  color: #183763;
  font-weight: 500;
  opacity: 0.8;
}

h3 {
  color: #2a4364;
  font-weight: 600;
  opacity: 0.8;
}
.circle1,
.circle2 {
  background: white;
  background: linear-gradient(
    to right bottom,
    rgba(255, 255, 255, 0.8),
    rgba(255, 255, 255, 0.3)
  );
  height: 20rem;
  width: 20rem;
  position: absolute;
  border-radius: 50%;
}

.circle1 {
  top: 5%;
  right: -5%;
}
.circle2 {
  bottom: 5%;
  left: -10%;
}
</style>
