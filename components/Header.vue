<template>
  <div class="main-header">
    <Container>
      <div class="main-header__content">
        <NuxtLink class="logo" to="/">
          <img src="../assets/images/logo.png" />
        </NuxtLink>
        <nav class="main-nav">
          <ul>
            <li>
              <NuxtLink to="/">Welcome</NuxtLink>
            </li>
            <li>
              <NuxtLink to="/products">Products</NuxtLink>
            </li>
            <li>
              <NuxtLink to="/promotions">Promotions</NuxtLink>
            </li>
            <li>
              <NuxtLink to="/events">Event / News</NuxtLink>
            </li>
            <li>
              <NuxtLink to="/about">About</NuxtLink>
            </li>
            <li>
              <NuxtLink to="/contact">Contact</NuxtLink>
            </li>
          </ul>
        </nav>
      </div>
    </Container>
  </div>
</template>

<style scoped>
/* Main Header */
.main-header {
  border-bottom: 1px solid #c0c0c0;
}
.main-header__content {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
/* Logo */
.logo {
  display: inline-block;
}
.logo img {
  width: 120px;
  height: auto;
}
/* Main Navigation */
.main-nav ul li {
  display: inline-block;
}
.main-nav ul li a {
  margin-left: 30px;
  font-size: 14px;
  color: #939393;
  text-decoration: none;
}
.main-nav ul li a:hover,
.main-nav ul li a.router-link-exact-active {
  color: #000;
}
</style>
