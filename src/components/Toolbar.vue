

<template>

  <div>
    <v-toolbar>
      <v-hover
        v-slot="{ hover }"
        open-delay="200"
      >
        <v-card
          :elevation="hover ? 16 : 2"
          :class="{ 'on-hover': hover }"
        >
          <v-icon>mdi-account</v-icon>
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