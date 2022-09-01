<template>
   <div class="navbar">

      <ul class="first-nb-section">
         <li class='li-circle'>
            <NuxtLink class="nuxtLinkStyle circle" to="#">D </NuxtLink>
         </li>
         <li>
            <NuxtLink class="nuxtLinkStyle" to="#">LEARN</NuxtLink>
         </li>
         <li>
            <NuxtLink class="nuxtLinkStyle active" to="#">BLOG</NuxtLink>
         </li>
         <li>
            <NuxtLink class="nuxtLinkStyle" to="#">BOOKMARKS</NuxtLink>
         </li>
         <li>
            <NuxtLink class="nuxtLinkStyle" to="#">UI KIT</NuxtLink>
         </li>
         <li>
            <NuxtLink class="nuxtLinkStyle" to="#">LAIN NYA</NuxtLink>
         </li>
      </ul>


      <ul class="second-nb-section">
         <li>
            <a href="https://twitter.com/?lang=en" target="_blank">
               <!-- <font-awesome-icon :icon="['fa-brands', 'fa-twitter']" class="icon-color" /> -->
               <img style="width:20px;filter:invert(42%) sepia(50%) saturate(13%) brightness(119%) contrast(2%);" src="https://www.dwinawan.com/img/icon_twitter.svg">
            </a>
         </li>
         <li>
            <a href="https://www.instagram.com/">
               <!-- <font-awesome-icon icon="fa-brands fa-instagram" class="icon-color" /> -->
               <img style="width:20px;filter:invert(42%) sepia(50%) saturate(13%) brightness(119%) contrast(2%);" src="https://www.dwinawan.com/img/icon_instagram.svg">
            </a>
         </li>
         <li>
            <a href="https://www.basketnews.lt/">
               <!-- <font-awesome-icon icon="fa-brands fa-dribbble" class="icon-color" /> -->
               <img style="width:20px;filter:invert(42%) sepia(50%) saturate(13%) brightness(119%) contrast(2%);" src="https://www.dwinawan.com/img/icon_dribbble.svg">
            </a>
         </li>
         <li>
            <a href="#">
               <!-- <font-awesome-icon icon="fa-brands fa-42-group" class="icon-color" /> -->
               <img style="width:20px;filter:invert(42%) sepia(50%) saturate(13%) brightness(119%) contrast(2%);" src="https://www.dwinawan.com/img/icon_medium.svg">
            </a>
         </li>
         <li class="show-menu-mobile"><a href='#'><img  src="https://www.dwinawan.com/img/icon_burger_white.svg"/></a></li>
      </ul>
   </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
   name: "Header"
})
</script>

<style scoped>
</style>