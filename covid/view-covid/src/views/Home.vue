<template>
  <div class="home">
    <v-container class="my-1">
      <v-row>
        <v-col>
          <div class="display-1"><b>Dashboard</b> Coronavírus teste</div>
          <div class="grey--text">Atualizado em: hh:mm dd/mm/yyyy</div>
        </v-col>
      </v-row>

      <v-row class="mx-5">
        <v-col>
          <v-card width="250px">
            <v-card-text class="display-1 text-center blue--text text--darken-4">12345</v-card-text>
            <v-card-title class="kpi confirmados justify-center pa-0">Casos confirmados</v-card-title>
          </v-card>
        </v-col>

        <v-col >
           <v-card width="250px">
            <v-card-text class="display-1 text-center red--text text--darken-1">12345</v-card-text>
            <v-card-title class="kpi obitos justify-center pa-0">Óbitos</v-card-title>
          </v-card>
        </v-col>

        <v-col>
           <v-card width="250px">
            <v-card-text class="display-1 text-center green--text text--accent-4">12345</v-card-text>
            <v-card-title class="kpi recuperados justify-center pa-0">Recuperados</v-card-title>
          </v-card>
        </v-col>

      </v-row>
      </v-container>
  </div>
</template>

<script>

export default {
  data() {
    return {
      
    }
  }

}
</script>

<style>

.kpi.confirmados {
  border-left: 4px solid #0D47A1
}
.kpi.obitos {
  border-left: 4px solid #E53935
}
.kpi.recuperados {
  border-left: 4px solid #00C853
}

</style>