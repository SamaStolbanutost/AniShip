<template>
  <v-container fluid class="main">
    <v-card class="rounded-lg pa-8" width="30vw" color="primary">
      <v-row class="align-center">
        <a href="https://progzone122.github.io/anderia-minigame/" target="_blank"><img
          src="~/assets/logo.svg" alt=""
          srcset="" class="aniship-icon"
        ></a>
        <v-col>
          <h1>AniShip</h1>
          <p style="opacity: 0.9;">Версия: {{ suffix + version }}</p>
        </v-col>
      </v-row>
    </v-card>
  </v-container>
</template>
<script>
export default {
  name: 'Settings',
  layout: 'default',
  data () {
    return {
      suffix: 'night-',
      version: '0.0.3-2'
    }
  }
}
</script>
<style lang="scss">

</style>
<style scss lang="scss">
@import "~/assets/variables.scss";

.aniship-icon {
  width: 20vh;
  background-size: cover;
}
</style>
