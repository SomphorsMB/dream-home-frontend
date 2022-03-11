<template>
<section>
  <div class="bg-gray-100 pt-14 pb-16">
    <img src="../static/BLUE_Communications_floor_plan.png" class="home-layout absolute top-1 rotate-45" alt="">
    <div class="grid grid-cols-2 gap-4 w-9/12 mx-auto h-96">
      <div class="flex justify-end">
        <div class=" w-4/6 flex items-center">
          <div class="w-full">
            <h5 class="flex">
          <svg class="w-6 h-6 text-orange-600" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 21h7a2 2 0 002-2V9.414a1 1 0 00-.293-.707l-5.414-5.414A1 1 0 0012.586 3H7a2 2 0 00-2 2v11m0 5l4.879-4.879m0 0a3 3 0 104.243-4.242 3 3 0 00-4.243 4.242z"></path></svg>
          <span>Real Estate Agency</span>
        </h5>
        <h1 class="text-4xl font-bold">Find Your Dream House By Us</h1>
        <div class="py-3">
        <small>Lorem ipsum dolor sit amet consectetur adipisicing elit</small>

        </div>
        <div class="mt-2">
          <button class="p-2 bg-orange-600 text-white">View Properites</button>
        </div>
          </div>
        </div>
      </div>
      <div class="">
        <img src="https://www.mypattayacondo.com/wp-content/uploads/2018/11/house-transparent-villa-2.png" alt="">
      </div>
    </div>

  </div>
      <div class="">
      <div class="card bg-white w-2/4 mx-auto rounded shadow flex justify-between p-4">
        <select name="cars" id="cars" class="border p-2 rounded w-44">
          <option value="volvo">Volvo</option>
          <option value="saab">Saab</option>
          <option value="mercedes">Mercedes</option>
          <option value="audi">Audi</option>
        </select>
        <select name="cars" id="cars" class="border p-2 rounded w-44">
          <option value="volvo">Volvo</option>
          <option value="saab">Saab</option>
          <option value="mercedes">Mercedes</option>
          <option value="audi">Audi</option>
        </select>
        <select name="cars" id="cars" class="border p-2 rounded w-44">
          <option value="volvo">Volvo</option>
          <option value="saab">Saab</option>
          <option value="mercedes">Mercedes</option>
          <option value="audi">Audi</option>
        </select>
        <button class="shadow py-2 px-6 rounded bg-orange-600 text-white ">
          Find Now
        </button>
      </div>

      <leading />

      <box />

      <div class="pb-8">
        <div class="text-center">
          <span
            class="mx-auto inline-block rounded-full px-3 py-1 text-sm font-semibold bg-orange-300 text-white mr-2 mb-2">Our Service</span
          >
           <h1 class="text-4xl font-bold">Featured Listings</h1>
        </div>

        <div class="px-14 grid grid-cols-4 gap-4 pt-8">
          <caerd  v-for="n in 4" :key="n" />
        </div>
        
      </div>
      <div class="text-center mb-16">
          <button class="ease-out duration-300 bg-transparent mx-auto hover:bg-orange-400 text-orange-600 font-semibold hover:text-white py-2 px-8 border border-orange-600 hover:border-transparent">
            View More
          </button>
      </div>


      <div class="bg-gray-100 py-10 mb-16">
        <div class="text-center">
          <span
            class="mx-auto inline-block rounded-full px-3 py-1 text-sm font-semibold bg-orange-300 text-white mr-2 mb-2">Our Service</span
          >
           <h1 class="text-4xl font-bold">Our Main Focus</h1>
        </div>
        <service />
      </div>

      <div class=" py-10 mb-16">
        <div class="text-center">
          <span
            class="mx-auto inline-block rounded-full px-3 py-1 text-sm font-semibold bg-orange-300 text-white mr-2 mb-2">Properties</span
          >
           <h1 class="text-4xl font-bold">Featured Listings</h1>
        </div>
        <feature-list />
      </div>
      </div>
    <!-- </div> -->
</section>
</template>

<script>
import box from './box.vue'
import Caerd from './Card.vue'
import FeatureList from './FeatureList.vue'
import Leading from './Leading.vue'
import Service from './Service.vue'
export default {
  components: { box, Caerd, Service, FeatureList, Leading },

}
</script>

<style scoped>
  .card{
    margin-top: -38px;
  }

  .home-layout{
    left: -15rem;
  }
</style>