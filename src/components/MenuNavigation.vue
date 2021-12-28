<template>
  <v-app-bar
    app
    color="green lighten-5"
    dark
  >
    <div class="d-flex align-center">
      <v-img
        alt="Health Oracle Protocol"
        class="shrink mr-2"
        contain
        src="@/assets/logo.png"
        transition="scale-transition"
        width="24"
      />
    <v-toolbar-title class="green--text darken-1--text">Truth as a Public Good</v-toolbar-title>
    </div>

    <v-spacer></v-spacer>
      <!-- <v-btn flat>SIGN IN</v-btn>
      <v-btn color="brown lighten-3">JOIN</v-btn> -->
  </v-app-bar>
</template>

<script>
export default {
  name: 'MenuNavigation',
  data: () => ({
  })
}
</script>
