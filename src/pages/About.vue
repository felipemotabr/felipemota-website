<template>
  <Layout>
    <div class="container">
      <div class="contact-header">
        <h1 class="contact-title">Olá!</h1>
        <p>
          Me chamo Felipe Mota, graduado em Publicidade e Propaganda e técnico
          em Comunicação Visual. Tenho trabalhado ao longo tempo em projetos de
          desenvolvimento de software, em Programação Front-end de aplicações
          para Web. Venho desempenhando Design de Interface em projetos para
          Mobile e Smartwatch.
        </p>
        <h3>Habilidades</h3>
        <ul>
          <li>Adobe Photoshop</li>
          <li>Adobe Illustrator</li>
          <li>Adobe XD</li>
          <li>Figma</li>
          <li>HTML5</li>
          <li>CSS3</li>
          <li>Sass</li>
          <li>Gulp</li>
          <li>PHP</li>
          <li>Javascript</li>
          <li>Jquery</li>
          <li>NodeJS</li>
          <li>Git</li>
        </ul>
        <h3>Frameworks</h3>
        <ul>
          <li>Wordpress</li>
          <li>Laravel</li>
          <li>Jekyll</li>
          <li>Bootstrap</li>
          <li>Scrum</li>
        </ul>
      </div>

      <form class="contact-form" name="contact">
        <h1 class="contact-title">Vamos bater um papo?</h1>
        <div class="sender-info">
          <div>
            <label for="name" class="label">Seu nome</label>
            <input type="text" name="name" />
          </div>
          <div>
            <label for="email" class="label">Seu e-mail</label>
            <input type="email" name="email" />
          </div>
        </div>

        <div class="message">
          <label for="message" class="label">Mensagem</label>
          <textarea name="message"></textarea>
        </div>

        <button class="button">Enviar</button>
      </form>
    </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Sobre",
  },
};
</script>

<style scoped>
.contact-header {
  padding: 2rem 0 4rem 0;
}
.contact-title {
  font-size: 4rem;
  margin: 0 0 4rem 0;
  padding: 0;
}
.sender-info {
  display: flex;
  flex-wrap: wrap;
  margin-bottom: 2rem;
}
.sender-info > div {
  flex: 1;
  margin-right: 4rem;
}
.sender-info > div:last-of-type {
  margin: 0;
}
input:focus,
textarea:focus {
  border-color: var(--color-contrast-1);
}
input,
textarea {
  background: transparent;
  border: 1px solid var(--color-base-1);
  outline: none;
  border-radius: 0.3rem;
  padding: 0.8rem 1rem;
  color: inherit;
  font-size: 1rem;
  width: 100%;
}
textarea {
  resize: none;
  height: 140px;
}
.button {
  color: var(--color-base);
  background: var(--color-contrast);
  outline: none;
  border: 0;
  font-size: 0.8rem;
  padding: 0.8rem 1.6rem;
  border-radius: 0.3rem;
  margin-top: 2rem;
  cursor: pointer;
  transition: opacity 0.25s ease;
  font-size: 500;
  letter-spacing: 0.035em;
}
.button:hover {
  opacity: 0.6;
}
.button:focus {
  border: 1px solid var(--color-base-1);
}
</style>
