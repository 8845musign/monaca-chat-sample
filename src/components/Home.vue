<template id="home">
  <v-ons-page>
    <v-ons-toolbar>
      <div class="center">HOME</div>
    </v-ons-toolbar>

    <div class="content">
      <v-ons-button @click="push">PUSH</v-ons-button>
    </div>
  </v-ons-page>
</template>

<script>
import Chat from './Chat'

export default {
  methods: {
    push () {
      this.$emit('push-page', Chat)
    }
  }
}
</script>

<style scoped>
</style>
