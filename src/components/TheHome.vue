<script setup lang="ts">
</script>

<template>
  <section class="dFlex homeContainer">
    <figure class="dFlex halfFlex">
      <img src="src/images/ntr-1.png" alt="Ntr" class="homeImg">
    </figure>
    <section class="backBg halfFlex">
      <aside class="content">
        <figure class="logo">
          <img src="src/images/logo.png" alt="Tarnaka Kammas" class="logo">
        </figure>
        <header>
          <h3>We are</h3>
          <h2>Coming Soon</h2>
        </header>
        <article>
          <p>Our website is under construction, please follow here for more updates</p>
        </article>
        <footer>
          <p>Get in touch with us @ </p>
          <a href="mailto:tarnakakammas@gmail.com">tarnakakammas@gmail.com</a>
        </footer>
      </aside>
    </section>
  </section>
</template>

<style scoped>
.homeContainer {
  min-height: 100vh;
  width: 100vw;
  flex-direction: row;
  background: rgb(250,247,255);
  background: linear-gradient(to right, rgba(250,247,255,1) 0%, rgba(239,229,124,1) 33%, rgba(249,221,97,1) 66%, rgba(230,175,46,1) 100%);
}
figure {
  margin: 0;
}
.halfFlex {
  flex: 50%;
}
.homeContainer figure img.homeImg {
  max-width: 100%;
  max-height: 100%;
  display: block;
  margin: auto;
}
.backBg {
  display: flex;
  flex-direction: column;
}
.backBg figure img.logo {
  max-width: 300px;
  display: block;
  margin: 0 auto;
  padding-bottom: 20px;
}
.dFlex {
  display: flex;
}
.content {
  text-align: center;
  margin: auto;
  color: #303030;
  line-height: 1.5;
  letter-spacing: 0.2px;
  padding: 0 24px;
}
.content header h3 {
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
@media (max-width: 991px) {
  .homeContainer {
    flex-direction: column;
    background: rgb(250,247,255);
    background: linear-gradient(to bottom, rgba(250,247,255,1) 0%, rgba(239,229,124,1) 33%, rgba(249,221,97,1) 66%, rgba(230,175,46,1) 100%);
  }
  .halfFlex {
    flex: 1;
  }
  .backBg {
    padding-top: 36px;
    padding-bottom: 48px;
  }
  .content header h2 {
    font-size: 36px;
  }
}
</style>
