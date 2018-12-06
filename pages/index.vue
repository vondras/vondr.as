<template>
  <main>
    <b-container fluid="">
      <section class="cover py-5 px-3">
        <div>
          <h1 class="name .text-align-sm-center .text-align-lg-right">
            Clayton<br>VonDras
          </h1>
        </div>
      </section>
    </b-container>
    <div
      class="text-white"
      style="background-color: #222;">
      <b-container class="py-5 bt-3">
        <section
          id="intro">
          <!-- eslint-disable -->
          <vue-markdown>
# Welcome to my site.

> It's incomplete, but it might be ready soon. Just you [wait](https://en.wikipedia.org/wiki/Heat_death_of_the_universe)!

          </vue-markdown>
        </section>
      </b-container>
    </div>
  </main>
</template>

<script>
import VueMarkdown from 'vue-markdown'

export default {
  components: {
    VueMarkdown
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Fira+Mono:400,500,700|IBM+Plex+Mono:100,100i,200,200i,300,300i,400,400i,500,500i,600,600i,700,700i|Roboto+Mono:100,100i,300,300i,400,400i,500,500i,700,700i&subset=greek,latin-ext');
/* @import url('https://fonts.googleapis.com/css?family=IBM+Plex+Mono:100,100i,200,200i,300,300i,400,400i,500,500i,600,600i,700,700i|Libre+Franklin:100,100i,200,200i,300,300i,400,400i,500,500i,600,600i,700,700i,800,800i,900,900i|Roboto+Mono:100,100i,300,300i,400,400i,500,500i,700,700i&subset=greek,latin-ext'); */

* {
  font-family: 'IBM Plex Mono', 'Gill Sans', 'Gill Sans MT', Calibri,
    'Trebuchet MS', sans-serif;
}

h1,
h2,
h3 {
  text-transform: uppercase;
  font-weight: lighter;
}

.name {
  font-weight: bolder;
  font-family: 'Roboto Mono', monospace;
  line-height: 0.75;
  text-transform: uppercase;
}
.text-blue {
  color: midnightblue;
}
.cover {
  background-image: url('/images/constellation-clayton.png');
  background-size: contain;
  background-position: 0 bottom;
  background-origin: 0;
  background-repeat: no-repeat;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>
