<template>
  <v-layout>
    <NavBar></NavBar>
    <v-main>
      <router-view />
    </v-main>
  </v-layout>
</template>

<script>
 import NavBar from "./components/NavBar.vue"

  export default {
    name: 'app',
    components: { NavBar },
    data() {
      return {
        //
      }
    }
  }
</script>
