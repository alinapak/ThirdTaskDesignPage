<template>
   <div class="card">
      <img class='image' :src="require(`~/assets/images/${card.image}` || `x.jpg`)" :alt="card.title" />
      <div class="card-container">
         <p class="date">{{ card.date }}</p>
         <h1 class="title">{{ card.title }}</h1>
         <p class="description">{{ card.description }}</p>
      </div>
   </div>
</template>

<script>
export default {
   props: ['card']
}
</script>

<style scoped>
</style>