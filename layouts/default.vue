<template>
  <v-app dark>
    <Header />
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>
    <Footer />
  </v-app>
</template>

<script>
import Header from '~/components/layout/Header'
import Footer from '~/components/layout/Footer'

export default {
  components: {
    Header,
    Footer
  }
}
</script>
