<template>
  <v-layout
    row
    justify-start
    align-center
  >
    <v-flex
      xs12
      sm8
      md4
    >
      <v-card
        hover
        to="/share"
      >
        <v-card-title
          class="headline teal--text font-weight-bold">SNS Share URL Generator
        </v-card-title>
        <v-spacer/>
        <v-card-text>
          <p>Twitter facebook LINEのシェア文の生成ツール</p>
        </v-card-text>
      </v-card>
    </v-flex>

  </v-layout>
</template>

<style>
  a{
    text-decoration: none;
  }
</style>

<script>
  import Logo
    from '~/components/Logo.vue';
  import VuetifyLogo
    from '~/components/VuetifyLogo.vue';

  export default {
    components: {
      Logo,
      VuetifyLogo
    }
  };
</script>
