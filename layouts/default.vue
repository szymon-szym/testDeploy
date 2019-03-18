<template>
  <div>
    <header class="p-3 h-10 w-full absolute block bg-primary text-white flex items-center justify-between">
      <h1>Nuxt + Tailwind CSS</h1>
      <a href="/contact">contact</a>
    </header>
    <div class="h-screen bg-grey flex items-center justify-around">
      <nuxt/>
    </div>
    <footer class="absolute p-3 h-10 w-full bg-black text-white flex items-center justify-between pin-b">
      <p><small>Ben</small></p>
      <p><small>&copy; copyright</small></p>
    </footer>
  </div>
</template>

<style>
h1 {
  @apply text-sm
}

a {
  @apply text-link no-underline
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
