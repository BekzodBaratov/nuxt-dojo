<template>
  <div>
    <header class="shadow-sm bg-white">
      <nav class="container mx-auto p-4 flex justify-between items-center">
        <NuxtLink class="font-bold" to="/">Nuxt judo</NuxtLink>
        <ul class="flex gap-4">
          <li><NuxtLink class="font-bold" to="/">Home</NuxtLink></li>
          <li><NuxtLink class="font-bold" to="/about">About</NuxtLink></li>
          <li><NuxtLink class="font-bold btn" to="/products">Products</NuxtLink></li>
        </ul>
      </nav>
    </header>

    <div class="container mx-auto my-12">
      <slot />
    </div>
  </div>
</template>

<style scoped>
.router-link-active {
  color: green;
}
</style>
