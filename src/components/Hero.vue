<template>
  <div class="hero-body">
    <div class="content">
      <p class="title">Hi I'm Stephen!</p>
      <p class="header-one">
        Open Source fullstack developer focusing on Javascript, Typescript and
        DevOps. <br />Community builder, Content Creator, Public Speaker and GitHub
        Star.
      </p>
      <div class="buttons">
        <RouterLink to="/about" class="btn-secondary">About me</RouterLink>
        <RouterLink to="/services" class="btn-primary">Work with me</RouterLink>
      </div>
    </div>
  </div>
</template>

<style scoped>
.hero-body {
  height: 70vh;
  display: flex;
  align-items: center;
  padding: 0px 10%;
  background-image: url(../assets/symbol-scatter-haikei_2.png);
  background-repeat: no-repeat;
  background-position:right right right;
  background-size: cover;
}
</style>
