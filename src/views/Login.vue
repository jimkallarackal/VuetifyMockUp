<template>
<v-container class="fill-height">
  <v-responsive class="d-flex align-center text-center fill-height">
    <v-img
      contain
      height="300"
      src="@/assets/logo.svg"
    />

    <div class="text-body-2 font-weight-light mb-n1">Login to </div>

    <h1 class="text-h2 font-weight-bold">Vuetify</h1>

    <div class="py-14" />

    <v-row class="d-flex align-center justify-center">
      <v-col cols="auto">
        <v-btn
          min-width="164"
          rel="noopener noreferrer"
          target="_blank"
          variant="text"
        >
          <v-icon
            icon="mdi-view-dashboard"
            size="large"
            start
          />

          Login
        </v-btn>
      </v-col>
    </v-row>
  </v-responsive>
</v-container>
</template>

<script setup>

</script>
