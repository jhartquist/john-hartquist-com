<template>
  <v-app>
    <v-app-bar app color="black" dark flat>
      <div class="d-flex align-center">
        john hartquist
      </div>
    </v-app-bar>

    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'App',

  data: () => ({
    //
  }),
})
</script>
