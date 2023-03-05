<template>
  <v-app>
    <v-main>
      <v-container fluid>
        <Nuxt />
      </v-container>
    </v-main>
    <v-footer>
      <v-container fluid>
      <v-row align="center" justify="space-between">
         <v-col cols="3">
          <v-card
      class="mx-auto"
      tile
    >
  
      <v-list-item three-line>
        <v-list-item-content>
          <v-list-item-title class="font-weight-bold text-subtitle">Address:</v-list-item-title>
          <v-list-item-subtitle>
            S1 Shivam apartment,Samrath Chowk,South shivajinagar,
          </v-list-item-subtitle>
          <v-list-item-subtitle>
            Sangli 416416, Maharashtra.
          </v-list-item-subtitle>
        </v-list-item-content>
      </v-list-item>
    </v-card>
         </v-col>
          <v-col cols="auto">
          <v-card
      class="mx-auto"
      tile
    >
  
      <v-list-item three-line>
        <v-list-item-content>
          <v-list-item-title class="font-weight-bold text-subtitle">Mobile:</v-list-item-title>
          <v-list-item-subtitle>
            (+91)8459271766
          </v-list-item-subtitle>
        </v-list-item-content>
      </v-list-item>
    </v-card>
         </v-col>
           <v-col cols="auto">
          <v-card
      class="mx-auto"
      tile
    >
  
      <v-list-item three-line>
        <v-list-item-content>
          <v-list-item-title class="font-weight-bold text-subtitle">Email:</v-list-item-title>
          <v-list-item-subtitle>
            leovish.in@gmail.com
          </v-list-item-subtitle>
        </v-list-item-content>
      </v-list-item>
    </v-card>
         </v-col>
      <v-col cols="12">

  
      <div class="px-4 py-2 bg-black text-center">
        {{ new Date().getFullYear() }} — <strong>&copy; Leovish interiors & constructions</strong>
      </div>
      </v-col>
      </v-row>
     
      </v-container>
      
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: 'DefaultLayout',
  data () {
    return {
      clipped: false,
      drawer: false,
      fixed: false,
      icons: [
        'mdi-facebook',
        'mdi-linkedin',
        'mdi-instagram',
      ],
      items: [
        {
          icon: 'mdi-apps',
          title: 'Welcome',
          to: '/'
        },
        {
          icon: 'mdi-chart-bubble',
          title: 'Inspire',
          to: '/inspire'
        }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'Vuetify.js'
    }
  }
}
</script>
