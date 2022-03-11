<template>
  <div class="my-4">
      <div class="flex space-x-8">
          <div class="hover:cursor-pointer hover:underline hover:underline-offset-2  hover:text-orange-600 focus:underline-offset-2" @click.stop="index = 0">First Floor</div>
          <div class="hover:cursor-pointer hover:underline hover:underline-offset-2  hover:text-orange-600" @click.stop="index = 1">Second Floor</div>
          <div class="hover:cursor-pointer hover:underline hover:underline-offset-2  hover:text-orange-600" @click.stop="index = 2">Third Floor</div>
      </div>

      <div class="grid grid-cols-2 gap-4 mt-3">
          <div class="">
              <img :src="plans[index].layout" alt="">
          </div>
          <div class="py-8">
              <h1 class="text-2xl font-bold text-gray-700">Deluxe Portion</h1>
              <p class="text-sm text-gray-500 mt-5 ">{{ plans[index].description }}</p>
          </div>
      </div>
  </div>
</template>

<script>
export default {

    data(){
        return{
            index: 0,
            plans: [
                {
                    layout: 'https://wcs.smartdraw.com/floor-plan/img/template-floor-plan.png?bn=1510011143',
                    description: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Atque animi ut rerum unde? Nobis iusto et quam, delectus molestias commodi, a corporis aliquam asperiores voluptatem neque tempora suscipit veritatis voluptatum!'
                },
                {
                    layout: 'https://www.familyhomeplans.com/varnish-images/plans/41420/41420-2l.gif',
                    description: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Atque animi ut rerum unde? Nobis iusto et quam, delectus molestias commodi, a corporis aliquam asperiores voluptatem neque tempora suscipit veritatis voluptatum!'
                },
                {
                    layout: 'https://timbercreekapartmentliving.com/wp-content/uploads/2020/12/2-bed-1-and-a-half-bath-912-lower-small.jpg',
                    description: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit. Atque animi ut rerum unde? Nobis iusto et quam, delectus molestias commodi, a corporis aliquam asperiores voluptatem neque tempora suscipit veritatis voluptatum!'
                },
            ]
        }
    }
}
</script>

<style>

</style>