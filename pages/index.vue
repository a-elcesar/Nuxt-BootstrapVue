<template>
  <div id="bg">
    <section class="container">
      <div>
        <logo />
        <h1 class="title">
          <a id="limu" href="http://limu.tv" target="_blank">LIMU.TV</a>
        </h1>
        <h2 class="subtitle">
          Live Music Experience
        </h2>
        <div class="links">
          <a
            href="https://play.google.com/store/apps/details?id=com.limu.app"
            target="_blank"
            class="button--green"
          >Download Now <font-awesome-icon :icon="['fab', 'google-play']" /></a>
          <a
            href="https://www.tiket.com/"
            target="_blank"
            class="button--grey"
          >Buy Tickets <font-awesome-icon :icon="['fas', 'ticket-alt']" /></a>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
#bg {
  background-image: linear-gradient(to top right, grey, black);
}

#limu {
  text-decoration: none;
  color: #4a9ecfad;
}

#limu:hover {
  text-decoration: none;
  color:whitesmoke;
}

.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  /* display: block; */
  font-weight: 700;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 500;
  color: lightgreen;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
