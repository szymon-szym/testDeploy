<template>
  <div>
    <header class="p-3 h-10 w-full absolute block bg-deep text-white flex items-center justify-between">
      <h1 class="font-serif">CRL</h1>
      <nuxt-link class="text-white text-sm font-serif" to="/"> HOME </nuxt-link>
    </header>
    <div class="h-screen p-12 bg-deep flex items-start justify-around">
      <nuxt/>
    </div>
    <footer class="absolute p-3 h-10 w-full bg-deep text-white flex items-center justify-between pin-b">
      <p><small>2019</small></p>
      <p><small></small></p>
    </footer>
  </div>
</template>

<style>
h1 {
  @apply text-sm
}

a {
  @apply  no-underline
}

a:hover {
  @apply underline
}

/* Transitions using the page hook */
    page-enter-active, .page-leave-active {
      transition: all .30s ease-out;
    }
    .page-enter, .page-leave-active {
      opacity: 0;
      transform-origin: 50% 50%;
    }
</style>
