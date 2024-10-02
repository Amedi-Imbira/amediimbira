<template>
  <nav>
    <div class="navbar-brand">
      <!-- #TODO: In italics -->
      <h1>
        <RouterLink to="/">STEPHEN IMBIRA</RouterLink>
      </h1>
    </div>

    <div class="navbar-menu">
      <ul>
        <li>
          <RouterLink to="/services">Services</RouterLink>
          <!-- <a href="#">Services</a> -->
        </li>
        <li>
          <RouterLink to="/about">About</RouterLink>
        </li>
      </ul>
    </div>
    <RouterLink to="/contact" class="btn-primary">Enquire</RouterLink>
  </nav>
</template>

<style scoped>

@import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400..700&display=swap');

nav {
  display: flex;
  justify-content: flex-end;
  align-items: center;
  padding: 30px 10%;
}

.navbar-brand {
  margin-right: auto;
}

.navbar-brand h1 {
  font-family: "Dancing Script", cursive;
  font-optical-sizing: auto;
  font-weight: bold;
}

.navbar-menu ul li {
  display: inline-block;
  padding: 0px 20px;
}
</style>
