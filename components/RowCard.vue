<template>
  <div class="border shadow my-4">
    <div class="rounded overflow-hidden shadow-lg flex">
      <div class=" absolute p-2 bg-orange-500 text-white font-medium">
        For Rent
      </div>
      <img class="w-6/12 h-72  shadow " src="https://d2vho998xd1yud.cloudfront.net/property_thumb/property/11585/187799/1599744612-5f5a2a64b2d517.04002457.jpeg">
      <div class=" py-4 w-6/12">
        <div class="font-bold text-xl px-3 text-orange-600">$ 349,00/<small>Month</small></div>
        <div class="text-xl font-bold px-3">New Apartment Nice View</div>
        <!-- <p class="text-gray-700 text-sm px-3">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus quia,    </p>
         -->
         <div class="flex items-end ml-2">
          <svg class="w-6 h-6 text-xs text-gray-500" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path></svg>
          <p class="text-xs">Phnom Penh, Cambodia</p>
        </div>
        <div class="w-9/12 grid grid-cols-3 gap-4 p-4 mr-0">
          <div class=" border-r-2">
            <div class="flex items-center">
              <span class="text-gray-500 mr-1">3</span>
              <img src="https://www.svgrepo.com/show/14685/bed.svg" class="w-9" alt="">
            </div>
            <small class="text-gray-500">Bedrooms</small>
          </div>
          <div class="border-r-2">
             <div class="flex items-center">
              <span class="text-gray-500 mr-1">3</span>
              <img src="https://www.svgrepo.com/show/283377/relax-bathroom.svg" class="w-9" alt="">
            </div>
            <small class="text-gray-500">Bathrooms</small>
          </div>
            
          <div class="">
            <div class="flex items-center">
              <span class="text-gray-500 mr-1">3450</span>
              <img src="https://www.svgrepo.com/show/68346/obtuse-angle-of-135-degrees.svg" class="w-9" alt="">
            </div>
            <small class="text-gray-500">Squre Ft</small>
          </div>
          
        </div>
        <hr class="my-3">
        <div class="flex justify-between items-center pt-3 px-2">
          <div class="flex">
            <img class="w-10 h-10 rounded-full" src="https://jooinn.com/images/builder-2.jpg" alt="">
            <div class="ml-1">
              <p class="font-medium">Andrew Gafev</p>
              <p class="text-gray-500 mt-0 pt-0 text-xs">Estate Agency</p>
            </div>
          </div>
          <div class="flex">
            <nuxt-link to="/property_detail"><button class="shadow py-1 px-2 text-orange-600">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 8V4m0 0h4M4 4l5 5m11-1V4m0 0h-4m4 0l-5 5M4 16v4m0 0h4m-4 0l5-5m11 5l-5-5m5 5v-4m0 4h-4"></path></svg>
            </button></nuxt-link>
            <button class="shadow py-1 px-2 text-orange-600">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z"></path></svg>
            </button>
            <button class="shadow py-1 px-2 text-orange-600">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 9v3m0 0v3m0-3h3m-3 0H9m12 0a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
            </button>
          </div>
        </div>
      </div>
      
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
  .location{
    margin-top: -40px;
  }

</style>