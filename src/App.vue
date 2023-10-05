<template>
  <v-app>
    <v-app-bar
      app
      color="#172136"
      dark
    >
      <div class="d-flex align-center">
        <v-img
          alt="FastSplash Logo"
          class="shrink mr-2"
          contain
          src="./assets/isotipo.svg"
          transition="scale-transition"
          width="110"
        />

        <v-img
          alt="FastSplash Name"
          class="shrink mt-1 hidden-sm-and-down"
          contain
          min-width="100"
          src="./assets/logo-fastsplash.svg"
          width="220"
        />
      </div>

      <v-spacer></v-spacer>

      <v-btn
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
        text
      >
        <span class="mr-2">Christian Novoa</span>
      </v-btn>
    </v-app-bar>

    <v-main>
      <HelloWorld/>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
