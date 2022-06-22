<template>
  <v-app>
    <div class="ma-10">
      <v-card max-width="100%">
        <v-card-title class="pa-5 white--text">
          <v-icon color="primary">mdi-application-cog-outline</v-icon>
          <span class="primary--text ml-3"
            >Quadro de projetos</span
          ></v-card-title
        >
        <v-divider></v-divider>
        <v-card-text class="pa-10">
          <v-card class="primary" max-width="400px">
            <v-card-title
              ><v-icon color="white" class="mr-3" @click="test()"
                >mdi-menu</v-icon
              >
              <span class="white--text">Mais informações</span></v-card-title
            >
            <v-card-title class="white--text"
              ><h2>Nome projeto</h2></v-card-title
            >
          </v-card>
        </v-card-text>
      </v-card>
    </div>
  </v-app>
</template>

<script>
export default {};
</script>

<style></style>
