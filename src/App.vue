<template>
  <v-app>
    <v-app-bar app dark color="green">
      <v-toolbar-title> Vue Login Application</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn text rounded> Home </v-btn>
      <v-btn text rounded> About</v-btn>
      <v-btn text rounded> Login</v-btn>
      <v-btn text rounded> Contact Us</v-btn>
    </v-app-bar>
    <v-content>
      <v-card width="600" class="mx auto" mt="6">
        <v-card-title> Log In Area </v-card-title>
        <v-card-text>
          <v-text-field label="Username" prepend-icon="mdi-account-circle">
            <v-text-field label="Password" type="password" prepend-icon="mdi-lock"
            append append-icon="mdi-eye-off">
            
            </v-text-field>
          </v-text-field>
        </v-card-text>
        <v-divider></v-divider>
        <v-card-actions>
          <v-btn color="blue">Login</v-btn>
        </v-card-actions>
      </v-card>
    </v-content>
  </v-app>
</template>

<script>
export default {
  data()
   {  
  return}

}
</script>