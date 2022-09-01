<template>
   <div>
      <h1 class="second-section-title">{{cardsSection.title}}</h1>
      <div class="second-card-section">
      <SecondComponentCards
      v-for='card in cardsSection.cards'
      :key='card.id'
      :card='card'/>
      </div>
   </div>
</template>

<script>
import SecondComponentCards from './SecondComponentCards.vue';
   export default {
    props: ["cardsSection"],
    components: { SecondComponentCards }
}
</script>

<style lang="scss" scoped>

</style>