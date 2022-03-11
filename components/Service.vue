<template>
  <div class="grid grid-cols-3 gap-4 mx-auto w-8/12 mt-10">
      <div class="flex items-center justify-center h-96 bg-white shadow" v-for="data of service" :key="data.description">
          <div class="text-center px-3">
                <img  class="w-20 h-20 text-orange-600 mx-auto"  :src="data.image" alt="">
                <!-- <svg class="w-14 h-14 text-orange-600 mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 20H5a2 2 0 01-2-2V6a2 2 0 012-2h10a2 2 0 012 2v1m2 13a2 2 0 01-2-2V7m2 13a2 2 0 002-2V9a2 2 0 00-2-2h-2m-4-3H9M7 16h6M7 8h6v4H7V8z"></path></svg> -->
                <h1 class="text-2xl font-bold py-3">{{ data.title }}</h1>
                <p class="text-base">{{ data.description }}</p>

                <li class="list-none mt-10 flex justify-center font-medium text-orange-600">
                    <span>Find a Home</span>
                    <svg class="w-6 h-6 pt-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg>
                </li>
            </div>
      </div>
  </div>
</template>

<script>
export default {
    props: ['service']
}
</script>

<style>

</style>

