<template>
  <div class="container">
    <div>
      <h1 class="title">
        Contact Su Gaar
      </h1>
      <h2 class="subtitle">
        Contact Us Coming Soon
      </h2>
      <div class="links">
        <a
          href="/about"
          class="button--green"
        >
          About
        </a>
        <a
          href="/wholesale"
          class="button--grey"
        >
          Wholesale
        </a>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  head () {
    return {
      script: [{ src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }]
    }
  },
  components: {
  }
}
</script>

<style>
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
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
  display: block;
  font-weight: 300;
  font-size: 80px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 20px;
  color: #526488;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
