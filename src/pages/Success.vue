<template>
  <Layout>
    <div class="container">
      <div class="error">
        <h1>
          Mensagem enviada
        </h1>
        <p>Brevemente irei lhe responder.</p>
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
