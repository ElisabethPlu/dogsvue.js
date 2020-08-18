<template>
  <div class="text-center">
    <v-dialog
      v-model="dialog"
      width="500"
    >
      <template v-slot:activator="{ on, attrs }">
        <v-btn
          color="red darken-4"
          dark
          v-bind="attrs"
          v-on="on"
        >
          Cliquez moi
        </v-btn>
      </template>

      <v-card>
        <v-card-title class="headline grey lighten-2">
          Politique du site
        </v-card-title>

        <v-card-text>
          L'objectif du site est de m'entraîner. Mais aussi que vous reconnaissiez que les chiens sont les meilleurs compagnons du monde.
        </v-card-text>

          <v-divider></v-divider>

            <v-card-actions>
              <v-spacer></v-spacer>
                <v-btn
                  color="primary"
                  text
                  @click="dialog = false"
                  >
                    Je l'accepte
                </v-btn>
                  <v-btn
                    color="primary"
                    text
                    @click="dialog2 = false"
                    >
              <v-dialog
              v-model="dialog2"
              width="500"
              >
                <template v-slot:activator="{ on, attrs }">
                  <v-btn
                  color="primary"
                  text
                  v-bind="attrs"
                  v-on="on"
                  >
                    Je ne l'accepte pas
                </v-btn>
              </template>
            <v-card>
              <v-card-title class="headline grey lighten-2">
                Politique du site
              </v-card-title>
                <v-card-text>
                  Vous n'avez pas le choix d'accepter...
                </v-card-text>
                  <v-divider></v-divider>
                    <v-card-actions>
                      <v-spacer></v-spacer>
                        <v-btn
                          color="primary"
                          text
                          @click="dialog = false"
                          >
                            J'accepte
                        </v-btn>
                      </v-card-actions>
                    </v-card>
                  </v-dialog>
                </v-btn>
              </v-card-actions>
            </v-card>
          </v-dialog>
        </div>
      </template>

<script>
  export default {
    data () {
      return {
        dialog: false,
        dialog2: false,
      }
    },
  }
</script>
