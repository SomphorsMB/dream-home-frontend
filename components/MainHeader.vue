<template>
  <div class="bg-gray-100 pt-14 pb-16 h-64">
          <img src="../static/BLUE_Communications_floor_plan.png" class="home-layout absolute w-80 right-72 top-0 rotate-45" alt="">
          <div class="w-7/12 mx-auto h-40 flex items-center">
              <div class="">
                  <h1 class="text-6xl font-bold">{{ title }}</h1>
                  <div class="flex items-center pt-6">
                      <svg class="w-6 h-6 text-orange-600 mr-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"></path></svg>
                      <p>Home ></p>
                      <p class="ml-2">{{ subTitle }}</p>
                  </div>
              </div>
          </div>
      </div>
</template>

<script>
export default {
    props: ['title', 'subTitle']
}
</script>

<style>

</style>