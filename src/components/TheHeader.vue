<template>
  <div id="header">
    <div class="pic">
      <img id="pic" alt="Vue logo" src="../assets/noah.png" />
    </div>
    <div id="tag">
      <div id="name">
        <h1>Noah Cheptoo</h1>
      </div>
      <div id="title">
        <h2>Programmer | Full Stack Web Developer</h2>
      </div>
    </div>
    <div id="info">
      <h3>I am a Self tought programmer</h3>
    </div>
  </div>
</template>

<script>
export default {
  name: 'TheHeader',
}
</script>

<style lang="scss">
#header {
  background: white;
  min-height: 90vh;
  width: 25rem;
  background: linear-gradient(
    to right bottom,
    rgba(255, 255, 255, 0.7),
    rgba(255, 255, 255, 0.3)
  );
  border-radius: 2rem;
  z-index: 2;
  backdrop-filter: blur(2rem);
  #pic {
    height: 50%;
    width: 50%;
    margin-top: 3rem;
    margin-bottom: 3rem;
    border-radius: 40%;
  }
  #tag {
    background: linear-gradient(to right top, #65dfc9, #6cdbeb);
    border-radius: 2rem;
    color: white;
    padding: 1rem;
    position: relative;
  }
  #info {
    margin-top: 1.5rem;
  }
}
</style>