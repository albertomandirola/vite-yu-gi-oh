<script>
import CardMaker from './CardMaker.vue'

import { store } from '../store.js';
export default {
    components: {
        CardMaker
    },
    data() {
        return {
            store
        }
    },
}
</script>
<template lang="">
    <div class="col" v-for="(card, index) in store.CardData" :key="index">
        <img :src="card.card_images[0].image_url_small" alt="">
    </div>
    
</template>
<style lang="scss" scoped>
img {
    width: 100%;
}
</style>