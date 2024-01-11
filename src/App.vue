<script>
import axios from 'axios';

import AppHeader from './components/AppHeader.vue'
import CardList from './components/CardList.vue'

import { store } from './store.js';

export default {
  components: {
    AppHeader,
    CardList
  },
  data() {
    return {

    }
  },
  methods: {
    getCardData() {
      axios.get(store.endpoint).then((response) => {
        store.CardData = response.data.data
      })
    }
  },
  created() {
    this.getCardData();
  },

}
</script>
<template lang="">
  <body>
    <AppHeader />
    <main>
      <div class="container">
        <div class="row">
          <CardList />
        </div>
      </div>
    </main>
  </body>
</template>
<style lang="scss" >
@use './styles/generals.scss' as *;
</style>