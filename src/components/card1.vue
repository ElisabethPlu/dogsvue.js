<template>
  <v-card class="d-inline-block mx-auto">
    <v-container>
      <v-row justify="space-between">
        <v-col cols="auto">
          <v-img
            height="200"
            width="200"
            src="https://cdn.pixabay.com/photo/2015/06/08/15/02/pug-801826_1280.jpg"
          ></v-img>
        </v-col>

        <v-col
          cols="auto"
          class="text-center pl-0"
        >
          <v-row
            class="flex-column ma-0 fill-height"
            justify="center"
          >
            <v-col class="px-0">
              <v-tooltip top>
                <template v-slot:activator="{ on, attrs }">
              <v-btn icon color="red" v-bind="attrs" v-on="on">
                <v-icon>mdi-heart</v-icon>
              </v-btn>
            </template>
            <span>J'aime</span>
            </v-tooltip>
            </v-col>

            <v-col class="px-0">
                <v-tooltip right>
                <template v-slot:activator="{ on, attrs }">
              <v-btn icon color="blue" v-bind="attrs" v-on="on">
                <v-icon>mdi-bookmark</v-icon>
              </v-btn>
            </template>
            <span>J'aime</span>
            </v-tooltip>
            </v-col>

            <v-col class="px-0">
                <v-tooltip bottom>
                  <template v-slot:activator="{ on, attrs }">
              <v-btn icon color= "green" v-bind="attrs" v-on="on">
                <v-icon>mdi-thumb-up</v-icon>
              </v-btn>
            </template>
            <span>J'aime</span>
            </v-tooltip>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
  </v-card>
</template>
