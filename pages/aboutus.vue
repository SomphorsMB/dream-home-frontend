<template>
    <section>
        <main-header :title="'About Us'" :subTitle="'About Us'" />
        <leading />

        <div class="bg-gray-100">
            <div class="grid grid-cols-2 gap-4 w-8/12 mx-auto mt-16 py-10 ">
                <div class="">
                    <span
                        class=" inline-block rounded-full px-3 py-1 text-sm font-semibold bg-orange-300 text-white mr-2 mb-2">About Us</span
                    >
                    <h1 class="text-4xl font-bold">The Leading Real Estate Rental Marketplase</h1>
                    <div class="flex mt-8 hover:bg-orange-600 hover:text-white rounded p-3">
                        <div class="w-16 h-16 flex items-center justify-center rounded-full p-2 bg-orange-100">
                            <img class="w-8 h-8" src="https://www.svgrepo.com/show/274822/builder.svg" alt="">
                        </div>
                        <div class="w-96 ml-2">
                            <p class="text-lg font-bold hover:text-white">The Perfect Residency</p>
                        <p class="text-sm text-gray-400">Lorem ipsum dolor sit amet consectetur adipisicing elit. Suscipit laborum optio aliquam ipsa ea amet saepe</p>
                        </div>
                    </div>
                    <div class="flex mt-5 hover:bg-orange-600 hover:text-white rounded p-3">
                        <div class="w-16 h-16 flex items-center justify-center rounded-full p-2 bg-orange-100">
                            <img class="w-8 h-8" src="https://www.svgrepo.com/show/43575/message-in-a-speech-bubble.svg" alt="">
                        </div>
                        <div class="w-96 ml-2">
                            <p class="text-lg font-bold hover:text-white">Global Architect Expert</p>
                        <p class="text-sm text-gray-400">Lorem ipsum dolor sit amet consectetur adipisicing elit. Suscipit laborum optio aliquam ipsa ea amet saepe</p>
                        </div>
                    </div>
                    <div class="flex mt-5 hover:bg-orange-600 hover:text-white rounded p-3">
                        <div class="w-16 h-16 flex items-center justify-center rounded-full p-2 bg-orange-100">
                            <img class="w-8 h-8" src="https://www.svgrepo.com/show/11526/building-crane.svg" alt="">
                        </div>
                        <div class="w-96 ml-2">
                            <p class="text-lg font-bol hover:text-whited">Build-in Storage Cupboards</p>
                        <p class="text-sm text-gray-400">Lorem ipsum dolor sit amet consectetur adipisicing elit. Suscipit laborum optio aliquam ipsa ea amet saepe</p>
                        </div>
                    </div>
                </div>
                <div class="">
                    <img src="https://www.mypattayacondo.com/wp-content/uploads/2018/11/house-transparent-villa-2.png" class="h-full" alt="">
                    <!-- <img src="https://pngimage.net/wp-content/uploads/2018/06/villas-png-1.png" class="" alt=""> -->
                </div>
            </div>
        </div>

        <div class=" my-16">
        <div class="text-center">
          <span
            class="mx-auto inline-block rounded-full px-3 py-1 text-sm font-semibold bg-orange-300 text-white mr-2 mb-2">Our Service</span
          >
           <h1 class="text-4xl font-bold">Our Main Focus</h1>
        </div>
        <service :service="coreFocus" />
      </div>

       <div class=" py-16 bg-gray-100">
        <div class="text-center">
          <span
            class="mx-auto inline-block rounded-full px-3 py-1 text-sm font-semibold bg-orange-300 text-white mr-2 mb-2">Our Service</span
          >
           <h1 class="text-4xl font-bold">Our Core Service</h1>
        </div>
        <service :service="coreService" />
      </div>


    <div class="pb-16 my-16">
       <div class="flex justify-center">
           <div class="text-center ">
               <span
                    class="mx-auto inline-block rounded-full px-3 py-1 text-sm font-semibold bg-orange-300 text-white mr-2 mb-2">Our Agent</span
                >
               <h1 class="text-4xl font-bold ">Property Agent</h1>
               <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Molestiae, sit.</p>
           </div>
       </div>
       <div class="w-8/12 mx-auto grid grid-cols-3 gap-4 mt-10 mb-16">
            <agent-card v-for="n in 3" :key="n" />
            
       </div>
       <div class="flex justify-center">
           <button class="py-3 px-8 mt-4 font-medium border-2 border-orange-600 hover:text-white hover:bg-orange-600">View More</button>
       </div>
   </div>
      
    </section>
</template>

<script>
import Leading from '~/components/Leading.vue'
import MainHeader from '~/components/MainHeader.vue'
import Service from '~/components/Service.vue'
export default {
    components: { MainHeader, Leading, Service },
    layout: 'Navigation',
    data(){
        return{
            coreFocus:[
                {
                    title: 'Buy a home',
                    image: 'https://www.homeslistedby.com/static/media/sellHome.ad0d9ce3.png',
                    description: 'Over 1 million+ homes for sale available on the website, we can match you with a house you will want to call home.'
                },
                {
                    title: 'Rent a home',
                    image: 'https://cdn-icons-png.flaticon.com/512/2490/2490447.png',
                    description: 'Over 1 million+ homes for sale available on the website, we can match you with a house you will want to call home.'
                },
                {
                    title: 'Sell a home',
                    image: 'https://cdn1.iconfinder.com/data/icons/real-estate-266/64/Sale-House-512.png',
                    description: 'Over 1 million+ homes for sale available on the website, we can match you with a house you will want to call home.'
                },
            ],
            coreService:[
                {
                    title: 'Property Management',
                    image: 'https://www.svgrepo.com/show/194097/home-house.svg',
                    description: 'Over 1 million+ homes for sale available on the website, we can match you with a house you will want to call home.'
                },
                {
                    title: 'Mortgage Service',
                    image: 'https://cdn-icons-png.flaticon.com/512/2490/2490447.png',
                    description: 'Over 1 million+ homes for sale available on the website, we can match you with a house you will want to call home.'
                },
                {
                    title: 'Consulting Service',
                    image: 'https://cdn1.iconfinder.com/data/icons/real-estate-266/64/Sale-House-512.png',
                    description: 'Over 1 million+ homes for sale available on the website, we can match you with a house you will want to call home.'
                },
                {
                    title: 'Home Buying',
                    image: 'https://cdn-icons-png.flaticon.com/512/2490/2490447.png',
                    description: 'Over 1 million+ homes for sale available on the website, we can match you with a house you will want to call home.'
                },
                {
                    title: 'Home Selling',
                    image: 'https://cdn1.iconfinder.com/data/icons/real-estate-266/64/Sale-House-512.png',
                    description: 'Over 1 million+ homes for sale available on the website, we can match you with a house you will want to call home.'
                },
                {
                    title: 'Escrow Service',
                    image: 'https://cdn1.iconfinder.com/data/icons/real-estate-266/64/Sale-House-512.png',
                    description: 'Over 1 million+ homes for sale available on the website, we can match you with a house you will want to call home.'
                },
            ],
        }
    }
}
</script>

<style>

</style>