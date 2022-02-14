<template>
  <v-app-bar>
    <v-toolbar-title class="headline text-uppercase">
      <span>Vuetify</span>
      <span class="font-weight-light">Material Design</span>
    </v-toolbar-title>
    <v-spacer></v-spacer>
    <v-btn
        flat
        target="_blank"
    >
      <span class="mr-2"><a :href="vuetifyUrl">Latest Release</a></span>
    </v-btn>
  </v-app-bar>
  <v-content>
    <HelloWorld msg="Welcome to Your Vue.js App with Vuetify and Vite"/>
  </v-content>

</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  },
  data: () => {
    return {
      vuetifyUrl: 'https://github.com/vuetifyjs/vuetify/releases/tag/v3.0.0-alpha.12',
    }
  }
}
</script>
