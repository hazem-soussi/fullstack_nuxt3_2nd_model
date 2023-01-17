<script setup lang="ts">
import SiteMapGrid from "~~/components/elements/SiteMapGrid.vue";
const show = ref(true)
</script>

<template>

  <div class="min-h-screen relative">
    <img
			src="/img/back.jpg"
			alt="Advance Home"
			class="object-cover h-full w-full absolute inset-0 -z-0"
		/>
    <div class="h-full relative">
			<Header />
   
        <div class="text-center ">
          <img class="w-auto" src="/img/dude-type.png" alt="dude image">
          <p class="mt-2 text-3xl leading-8 font-extrabold tracking-tight md:text-7xl dark:text-white">
            Full Stack <span class="bg-clip-text text-transparent bg-gradient-to-r from-indigo-500 to-teal-400 hover:from-green-500 hover:to-teal-400">ZooMa Project</span>
          </p>
          <div class="flex justify-center">
          <site-map-grid />
          </div>
        </div>
			<Hero />
			
		</div>
    <div
      class="py-12 theme-mode dark:bg-black">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
     
      </div>
      <div class="flex justify-center my-20">
        <!-- <button @click="show = !show">Toggle Slide + Fade</button> -->
      </div>

    </div>
 
  </div>
</template>