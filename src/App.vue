<template>
  <b-container fluid>
      <app-header></app-header>
    <b-row class="mt-3">
      <b-col xl="8" offset-xl="2">
        <router-view></router-view>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue'

export default {
  components: {
    appHeader: Header
  }
}
</script>
