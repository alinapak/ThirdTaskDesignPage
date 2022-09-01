<template>
   <div>
      <h1 class="card-section-title">{{cardsSection.title}}</h1>
      <div class="cards-container">
         <FirstComponentCards
         class="card"
         v-for='card in cardsSection.cards'
         :key="card.id"
         :card='card'/>
      </div>
   </div>
</template>

<script>
import FirstComponentCards from './FirstComponentCards.vue';

export default{
    props: ["cardsSection"],
    components: { FirstComponentCards}
}
</script>

<style scoped>

</style>