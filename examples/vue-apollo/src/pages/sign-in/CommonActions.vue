<template>
  <oauth-links />
  <v-divider class="my-4" />
  <v-btn
    class="my-1"
    block
    variant="outlined"
    prepend-icon="mdi-lock"
    color="primary"
    to="/signin/passwordless"
  >
    Continue with passwordless email
  </v-btn>
  <v-btn
    class="my-1"
    block
    variant="text"
    color="primary"
    to="/signin/email-password"
  >
    Continue with email + password
  </v-btn>
</template>
