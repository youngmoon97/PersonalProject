<template>
  <v-app-bar flat>
    <v-app-bar-title class="text-h4 d-flex justify-center">
      <v-spacer></v-spacer>
      <v-icon size="large">
        <v-img src="@/assets/logo.jpg"></v-img>
      </v-icon>

      Honesty Justice
    </v-app-bar-title>
    <template v-slot:append>
      <v-btn icon="mdi-heart"></v-btn>

      <v-btn icon="mdi-account"></v-btn>

      <v-btn icon="mdi-dots-vertical"></v-btn>
    </template>
  </v-app-bar>
</template>

<script setup>
//
</script>
