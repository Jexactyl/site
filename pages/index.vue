<template>
  <div>
    <Spinner />
    <Navbar />
    <div class="grid h-full place-items-center">
      <img src="https://www.jexactyl.com/assets/images/logo.png" height="480" width="480" class="mt-10" />
      <p class="text-7xl px-4 font-bold text-white">Jexactyl: the next-gen Game Panel.</p>
      <p class="text-2xl px-4 font-semibold text-gray-400 mt-5 mb-10">Built on the latest frameworks with security and performance in mind.</p>
      <fa-icon icon="fa-solid fa-arrow-down" class="text-pink-700 h-6 w-6 my-8" />
    </div>
    <Features />
    <ImageSection />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Navbar from '@/components/Navbar/index.vue'
import Spinner from '@/components/Spinner/index.vue'
import Features from '@/components/Features/index.vue'
import ImageSection from '@/components/ImageSection/index.vue'
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'

Vue.component('fa-icon', FontAwesomeIcon)

export default Vue.extend({
    name: "Home",
    components: { Navbar, Spinner, Features, ImageSection }
})
</script>
