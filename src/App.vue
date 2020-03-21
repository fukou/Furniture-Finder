<template>
  <v-app class="wrapper">
    <v-content>
      <router-view></router-view>
    </v-content>
  </v-app>
</template>

<script>
export default {
  name: "App"
};
</script>

<style>
h1,
h2,
h3,
h4,
h5,
h6 {
  color: #111;
}

body {
  background-color: #eee;
}

.wrapper {
  margin: 5rem auto;
  max-width: 60rem;
  background: transparent !important;
}

@media (max-width: 60rem) {
  .wrapper {
    margin: 1rem auto;
  }
}

.chips > * + * {
  margin-left: 0.65rem;
}
</style>
