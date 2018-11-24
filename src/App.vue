<template id="main">
  <v-ons-navigator swipeabl :page-stack="pageStack" @push-page="pageStack.push($event)">
  </v-ons-navigator>
</template>

<script>
import Home from './components/Home'

export default {
  name: 'app',
  data () {
    return {
      pageStack: [Home]
    }
  }
}
</script>

<style scoped>
</style>
