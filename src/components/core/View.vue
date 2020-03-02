<template>
  <v-content>
    <div id="core-view">
      <v-fade-transition mode="out-in">
        <router-view />
      </v-fade-transition>
    </div>
    <core-footer v-if="$route.name !== 'Maps'" />
  </v-content>
</template>

<script>
import axios from 'axios'
export default {
  metaInfo () {
    return {
      title: 'Pharmacy Nak'
    }
  },
  mounted () {
    axios
      .get('https://api.coindesk.com/v1/bpi/currentprice.json')
      .then(response => (console.log(response.data)))
  }
}
</script>

<style>
#core-view {
  padding-bottom: 100px;
}
</style>
