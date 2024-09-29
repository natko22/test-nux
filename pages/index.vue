<template>
  <div>
    <header>
      <nav>
        <Nuxt-link to="/">Nuxt App</Nuxt-link>
        <ul>
          <li><NuxtLink to="/">Home</NuxtLink></li>
          <li><NuxtLink to="/about">About</NuxtLink></li>
          <li><NuxtLink to="/products">Products</NuxtLink></li>
        </ul>
      </nav>
    </header>
    <h2>Home</h2>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem vitae
      quibusdam numquam delectus veritatis quasi culpa. Dolore culpa atque vero
      veniam excepturi labore adipisci accusantium obcaecati tenetur. Excepturi,
      exercitationem consequatur!
    </p>
  </div>
</template>

<script lang="ts" setup></script>

<style>
h2 {
  margin-bottom: 20px;
  font-size: 36px;
}
p {
  margin: 20px 0;
}
</style>
