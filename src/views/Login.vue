<template>
  <div class="center">
      <v-row>
          <v-col cols="10" sm="6" md="4" offset-md="4" offset-sm="4" offset="1">
              <v-avatar color="primary" size="96" tile>
                  <v-img src="@/assets/logo.png"></v-img>
              </v-avatar>
              <v-text-field label="Username" v-model="username"></v-text-field>
              <v-text-field label="Password" v-model="password" type="password"></v-text-field>
              <v-btn block elevation="2" @click="authenticate()">Login</v-btn>
              <h1>Login Page</h1>
          </v-col>
      </v-row>
  </div>
</template>

<script>
  export default {
      data() {
          return {
              username: "",
              password: "",
          }
      },
      methods: {
          authenticate() {
              alert("Login CLicked")
          }
      },
  }
</script>

<style lang="scss" scoped>

</style>
