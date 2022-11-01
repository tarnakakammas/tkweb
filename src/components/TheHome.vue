<script setup lang="ts">
</script>

<template>
  <section class="backBg">
    <aside class="content">
      <header>
        <h1>Tarnaka Kammas <span>are</span></h1>
        <h2>Coming Soon</h2>
      </header>
      <article>
        <p>Our website is under construction, follow here for more updates</p>
      </article>
      <footer>
        <p>Get in touch with us @ </p>
        <a href="mailto:tarnakakammas@gmail.com">tarnakakammas@gmail.com</a>
      </footer>
    </aside>
  </section>
</template>

<style scoped>
.backBg {
  display: flex;
  flex-direction: column;
  width: 100vw;
  height: 100vh;
  background: -webkit-linear-gradient(bottom,#f77062,#fe5196);
  background: -o-linear-gradient(bottom,#f77062,#fe5196);
  background: -moz-linear-gradient(bottom,#f77062,#fe5196);
  background: linear-gradient(bottom,#f77062,#fe5196);
}
.content {
  text-align: center;
  margin: auto;
  color: #fff;
  line-height: 1.5;
  letter-spacing: 0.2px;
}
.content header h1 {
  font-size: 24px;
}
.content header h2 {
  text-transform: uppercase;
  font-size: 60px;
}
.content article p {
  margin-top: 24px;
  font-size: 24px;
}
.content footer p {
  margin-top: 36px;
}
.content footer a {
  color: #261924;
}
</style>
