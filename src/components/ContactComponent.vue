<template>
  <article class="contact-component left-line">
    <h1>Downloads</h1>
    <section class="contact-grid-column">
      <ul class="download-item">
        <li><a href="/cv/cv-gustav-hersmann-english.pdf" target="_blank"><img class="cv-img" src="/cv/cv-gustav-hersmann-english-thumbnail.png" width="100px"></a></li>
        <li><a href="/cv/cv-gustav-hersmann-english.pdf" target="_blank">Resumé in English.pdf</a></li>
      </ul>
      <ul class="download-item">
        <li><a href="/cv/lebenslauf-gustav-hersmann-deutsch.pdf" target="_blank"><img class="cv-img" src="/cv/cv-gustav-hersmann-english-thumbnail.png" width="100px"></a></li>
        <li><a href="/cv/lebenslauf-gustav-hersmann-deutsch.pdf" target="_blank">Lebenslauf auf Deutsch.pdf</a></li></ul>
    </section>
  </article>

  <article class="contact-component left-line">
    <h1>Contact</h1>
      <ul class="contact-item">
        <li><a href="mailto:gustav@gustavhersmann.com">gustav@gustavhersmann.com</a></li>
        <li><a href="tel:+4915221477147">+49 (0) 1522 1477147</a></li>
        <li><a href="https://github.com/ghersmann">github.com/ghersmann</a></li>
        <li><a href="https://www.linkedin.com/in/gustavhersmann">linkedin.com/in/gustavhersmann</a></li>
      </ul>
  </article>
</template>

<script>

export default {
  name: 'ContactComponent',
}
</script>

<style scoped>
.cv-img {
border: 1px solid black;
}

h1 {
  margin-bottom: 2rem;
}

a {
  text-decoration: none;
  line-height: 2rem;
}

.download-item {
  width: 26rem;
  margin: 0 auto;
  padding: 2rem;
  text-align: center;
}
</style>
