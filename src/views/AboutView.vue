<template>
  <v-responsive class="mx-auto" max-width="344">
    <v-text-field hide-details="auto" label="id"></v-text-field>
    <v-text-field hide-details="auto" label="account_id"></v-text-field>
    <v-text-field hide-details="auto" label="bank_id"></v-text-field>
    <v-text-field hide-details="auto" label="amount"></v-text-field>
    <v-text-field hide-details="auto" label="transaction_time"></v-text-field>
    
  </v-responsive>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
