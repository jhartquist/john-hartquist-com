<template>
  <v-app>
    <v-main>
      <router-view />
    </v-main>
    <v-footer color="white">
      <v-container>
        <v-row>
          <v-col class="ml-4">
            <v-divider width="600"></v-divider>
          </v-col>
        </v-row>
        <v-row>
          <v-col class="py-0 ml-4">
            <v-btn
              v-for="btn in btns"
              :key="btn.icon"
              class="mr-4"
              circle
              fab
              dark
              small
              elevation="0"
              color="#ccc"
              :href="btn.href"
              target="_blank"
            >
              <v-icon>{{ btn.icon }}</v-icon>
            </v-btn>
          </v-col>
        </v-row>
      </v-container>
    </v-footer>
  </v-app>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'App',

  data: () => ({
    btns: [
      { icon: 'mdi-email', href: 'mailto:john@hartquist.com' },
      {
        icon: 'mdi-linkedin',
        href: 'https://www.linkedin.com/in/john-hartquist/',
      },
      { icon: 'mdi-twitter', href: 'https://twitter.com/johnhartquist' },
      { icon: 'mdi-github', href: 'https://github.com/jhartquist' },
      { icon: 'mdi-facebook', href: 'https://www.facebook.com/jhartquist' },
    ],
  }),
})
</script>
