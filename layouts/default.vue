<template>
  <v-app dark>
    <v-app-bar
      fixed
      app
    >
      <Header />
    </v-app-bar>
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
import Header from '~/components/Header'

export default {
    name: "DefaultLayout",
    components: {
        Header
    },
    data() {
        return {};
    },
    components: { Header }
}
</script>
