<template>
  <div class="container">
    <div>
      <h1 class="title font-bold">
        Su <span class="text-green-700">Gaar</span>
      </h1>
      <h2 class="subtitle text-xl">
        Decadent <span class="text-green-700 font-bold">CBD</span> Products Coming Soon
      </h2>
      <!--<div class="links">-->
        <!--<a-->
          <!--href="/contact"-->
          <!--class="button&#45;&#45;green"-->
        <!--&gt;-->
          <!--Contact-->
        <!--</a>-->
        <!--<a-->
          <!--href="/wholesale"-->
          <!--class="button&#45;&#45;grey"-->
        <!--&gt;-->
          <!--Wholesale-->
        <!--</a>-->
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
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
  -webkit-animation: fadein 4s; /* Safari, Chrome and Opera > 12.1 */
  -moz-animation: fadein 4s; /* Firefox < 16 */
  -ms-animation: fadein 4s; /* Internet Explorer */
  -o-animation: fadein 4s; /* Opera < 12.1 */
  animation: fadein 4s;
}

.subtitle {
  font-weight: 300;
  color: #526488;
  padding-bottom: 15px;
  -webkit-animation: fadein 4s; /* Safari, Chrome and Opera > 12.1 */
  -moz-animation: fadein 4s; /* Firefox < 16 */
  -ms-animation: fadein 4s; /* Internet Explorer */
  -o-animation: fadein 4s; /* Opera < 12.1 */
  animation: fadein 4s;
}

.links {
  padding-top: 15px;
}

@keyframes fadein {
  from { opacity: 0; }
  to   { opacity: 1; }
}

/* Firefox < 16 */
@-moz-keyframes fadein {
  from { opacity: 0; }
  to   { opacity: 1; }
}

/* Safari, Chrome and Opera > 12.1 */
@-webkit-keyframes fadein {
  from { opacity: 0; }
  to   { opacity: 1; }
}

/* Internet Explorer */
@-ms-keyframes fadein {
  from { opacity: 0; }
  to   { opacity: 1; }
}

/* Opera < 12.1 */
@-o-keyframes fadein {
  from { opacity: 0; }
  to   { opacity: 1; }
}
</style>
