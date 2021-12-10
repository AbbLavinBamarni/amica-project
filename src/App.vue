<template>
  <v-app>
    <Toolbar />
    <Main />
  </v-app>
</template>

<script>
import Toolbar from './components/Toolbar'
import Main from './components/Main'

export default {
  name: 'App',

  components: {
    Toolbar, Main
  },

  data: () => ({
    //
  }),
};
</script>
