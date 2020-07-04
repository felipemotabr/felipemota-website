<template>
  <Layout>
    <div class="container">
      <div class="error">
        <h1>
          Página não encontrada
        </h1>
        <p>
          Retornar para o
          <g-link :to="{ name: 'home' }">início</g-link>
        </p>
      </div>
    </div>
  </Layout>
</template>
<style scoped>
.error {
  text-align: center;
  padding: 11em 0;
}
</style>
