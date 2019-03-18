<template>
  <div class="container">
    <div>
      <h1>Szymon</h1>
    </div>
  </div>
</template>


<script>
export default {
  asyncData() {
    return {
      name: (process.server ? 'server' : 'client')
    }
  }
}
</script>

<style scoped>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
h1 {
  font-weight: 400;
}
.name {
  color: #3b8070;
}
p {
  margin-top: 20px;
}
</style>