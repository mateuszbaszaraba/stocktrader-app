<template>
  <b-container>
    <b-row>
      <app-header></app-header>
      <router-view></router-view>
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
