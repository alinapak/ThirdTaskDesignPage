<template>
  <div>
    <Header />
    <FirstSectionComponent
    v-for="cardInfo in firstSectionInfo"
    :key="cardInfo.id"
    :cardsSection="cardInfo"
     />
     <SecondSectionComponent
     v-for="cardInfo in secondSectionInfo"
    :key="cardInfo.id"
    :cardsSection="cardInfo"/>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Header from '~/components/Header.vue';
import FirstSectionComponent from '~/components/FirstSectionComponent.vue';
import { firstCardSection, secondCardSection } from '@/assets/data.js';
import SecondSectionComponent from '~/components/SecondSectionComponent.vue';

export default Vue.extend({
  components: { Header, FirstSectionComponent, SecondSectionComponent },
  data() { 
    return{
      firstSectionInfo:firstCardSection,
      secondSectionInfo:secondCardSection
    } }
})
</script>
