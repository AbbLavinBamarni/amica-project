

<template>

  <div>
    <v-toolbar color="red darken-4">
      <v-hover v-slot="{ hover }">
        <v-card
          :elevation="hover ? 16 : 2"
          :class="{ 'on-hover': hover }"
        >
          <v-icon color="red darken-4">mdi-account</v-icon>
        </v-card>
      </v-hover>

    </v-toolbar>
  </div>
</template>

<script>
export default {

}
</script>

<style>
</style>