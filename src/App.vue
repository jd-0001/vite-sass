<template>
  <v-app>
    <v-main class="pa-6">
      <v-card title="Button">
        <v-card-content class="d-flex" style="gap: 1.5rem;">
          <v-btn color="primary">Primary</v-btn>
          <v-btn color="success">Success</v-btn>
          <v-btn color="warning">Warning</v-btn>
          <v-btn color="error">Error</v-btn>
        </v-card-content>
      </v-card>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',
  data: () => ({
    //
  }),
}
</script>

<style lang="scss">
.v-application {
  background-color: #f1f1f1 !important;
}
</style>