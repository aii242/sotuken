<template>
    <v-app>
        <header>
      <v-app-bar 
      class="px-5"
      color="teal-lighten-2"
      flat
      >
        <v-sheet class="bg-teal-lighten-2 text-h4 text-white">
            <NuxtLink to="/" class="home ms-7">
                Anytime Checker
            </NuxtLink>
                </v-sheet>
                <template v-slot:append>
                    <NuxtLink to="/calendar">
                        <v-btn icon class="mr-5">
                            <v-icon color="white">mdi-calendar</v-icon>
                        </v-btn>
                    </NuxtLink>
                    <NuxtLink to="/visit">
                        <v-btn icon class="mr-5">
                            <v-icon color="white">mdi-list-box</v-icon>
                        </v-btn>
                    </NuxtLink>
                </template>
            </v-app-bar>
        </header>
    </v-app>
</template>

<style scoped>
.home{
  color: white;
  text-decoration: none;
}
</style>

<script setup lang="ts">

</script>