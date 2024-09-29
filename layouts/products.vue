<template>
  <div>
    <header>
      <nav>
        <NuxtLink to="/products">Nuxt Prducts</NuxtLink>
      </nav>
    </header>
    <div>
      <slot />
    </div>
    <footer>
      <ul>
        <li><NuxtLink to="/">Home</NuxtLink></li>
        <li><NuxtLink to="/about">About</NuxtLink></li>
        <li><NuxtLink to="/products">Products </NuxtLink></li>
      </ul>
    </footer>
  </div>
</template>

<style scoped>
.router-link-exact-active {
  color: #3a6e60;
}
</style>
