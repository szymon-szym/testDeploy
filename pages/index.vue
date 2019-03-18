<template>
  <section>
    <div>
      <h2 class="subtitle">Really Really Awesome</h2>
      <p>Testing code here <nuxt-link to="about">go about</nuxt-link></p>
      <p>Go to Szymon <nuxt-link to="szymon">Szymon</nuxt-link>  </p>

    </div>
  </section>
</template> 

<script>
import Logo from '~/components/Logo.vue'
import IconLink from '~/components/IconLink.vue'

export default {
  components: {
    Logo,
    IconLink
  }
}
</script>

<style scoped>

</style>
