<script setup>
import { RouterLink, RouterView } from 'vue-router'
import MainHeader from '../src/components/MainHeader.vue'
import MainHero from '../src/components/MainHero.vue'
import MainCourses from '../src/components/MainCourses.vue'
import MainInstructors from '../src/components/MainInstructors.vue'
import MainAboutUs from '../src/components/MainAboutUs.vue'
import MainContact from '../src/components/MainContact.vue'

import MainFooter from '../src/components/MainFooter.vue'


</script>

<template>
  <div class="main-container">
    <MainHeader />
    <MainHero />
    <MainAboutUs />
    <MainCourses />
    <MainInstructors />
    <MainContact />
    
    <MainFooter />
    <RouterView />
  </div>
</template>

<style scoped>

</style>
