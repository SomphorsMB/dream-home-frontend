<template>
  <section>
      <main-header :title="'Properties Detail'" :subTitle="'Properties'"  />
      <div class="w-8/12 mt-10 mx-auto">
          <img src="http://www.dfive.hu/img/property/142/dfive-property-dfive-petofi-apartment-1-opt90.jpg" alt="">
      </div>

      <div class="grid grid-cols-3 gap-4 mb-16 w-8/12 mx-auto mt-10">
        <div class="col-span-2 grid grid-cols-1 gap-4">
            <div class="">
                <div class="flex justify-between">
                    <div class="flex">
                    <div class="py-1 px-3 uppercase bg-orange-600 text-white rounded">Featured</div>
                    <div class="py-1 px-3 mx-2 uppercase bg-purple-600 text-white rounded">For Rent</div>
                    <div class="flex">
                        <span class="flex items-center border-r-2 border-orange-300 pr-2 text-xs">
                            <svg class="w-4 h-4 text-orange-400 mr-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"></path></svg>
                            <span>Feb 28, 2022</span>
                        </span>
                        <span class="flex items-center ml-2 text-xs">
                            <svg class="w-4 h-4 text-orange-400 mr-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 8h10M7 12h4m1 8l-4-4H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-3l-4 4z"></path></svg>
                            <span>0 Comments</span>
                        </span>
                    </div>
                </div>
                
                <div class="flex">
                    
                    <button class="shadow py-1 px-2 text-orange-600">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z"></path></svg>
                    </button>
                    <button class="shadow py-1 px-2 text-orange-600">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 9v3m0 0v3m0-3h3m-3 0H9m12 0a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                    </button>
                </div>
                
                </div>


                <div class="my-5 flex justify-between">
                    <div class="">
                        <h1 class="text-3xl font-semibold capitalize ">Diamond Manor Apartment</h1>
                        <p class="flex items-center mt-3">
                            <svg class="w-4 h-4 mr-1 text-orange-600" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path></svg>
                            <span class="text-xs text-gray-500">Belmont Gardens, Cambodia</span>
                        </p>
                    </div>
                    <p class="text-orange-600 mt-2">
                        <span class="text-xl font-bold -mr-1">$ 349,00</span>
                        <span class="text-sm">/Month</span>
                    </p>
                </div>

                <div class="my-8">
                    <h3 class="pl-1 border-l-2 border-orange-400 text-lg font-medium">Description</h3>
                    <p class="my-4 text-base text-gray-500">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Perspiciatis eum fugit atque nesciunt cupiditate doloremque assumenda cumque consequuntur, est dolorem earum, debitis, voluptas ex officia dolores quos consequatur a error rerum quas molestias sint ad illo. Aspernatur rerum, repellat quisquam iure in mollitia. Perspiciatis aut corrupti eius doloremque ex obcaecati, ipsam repudiandae. Nobis, architecto placeat? Vero, dolores quibusdam! Consectetur aliquid optio maxime illo magnam soluta, facilis similique laboriosam perspiciatis harum magni voluptatem dolor dicta, fuga nisi nam, iste vero rerum facere nobis. Ipsum a consectetur, nostrum fugiat expedita facere aperiam pariatur nisi eligendi, recusandae nihil amet. Mollitia possimus minima dolores!</p>
                    
                </div>

                <div class="my-8">
                    <h3 class="pl-1 border-l-2 border-orange-400 text-lg font-medium">Property Detail</h3>
                    <property-info-detail />
                </div>

                <div class="my-8">
                    <h3 class="pl-1 border-l-2 border-orange-400 text-lg font-medium">Fact and Features</h3>
                    <div class="grid grid-cols-4 gap-4 my-4">
                        <feature v-for="m in 8" :key="m" />
                    </div>
                </div>

                <div class="my-8">
                    <h3 class="pl-1 border-l-2 border-orange-400 text-lg font-medium">From Our Gallery</h3>
                    <div class="grid grid-cols-2 gap-4 my-4">
                        <div class="">
                            <img class="h-52 w-full rounded" src="https://images.ctfassets.net/pg6xj64qk0kh/6BOkUsJuFaxNljqKAmLqbj/face0a409d1f56e628f380c657e0b035/camden-buckhead-apartments-atlanta-ga-amenity-deck-building-exterior-and-views-of-downtown-atlanta.JPG" alt="">
                            <img class="h-52 w-full mt-3 rounded" src="https://images.ctfassets.net/pg6xj64qk0kh/4DIzHOTo44IRiDC1nPiJow/9b176ced75448ff41a77758d6b69d337/camden-buckhead-apartments-atlanta-ga-saltwater-pool-with-cabanas.JPG" alt="">
                        </div>
                        <div class="">
                            <img class="h-full rounded" src="https://pbs.twimg.com/media/Exkwp8aWgAcxq0e.jpg" alt="">
                        </div>
                    </div>
                </div>

                <div class="my-8">
                    <h3 class="pl-1 border-l-2 border-orange-400 text-lg font-medium">Amenities</h3>
                    <div class="grid grid-cols-3 gap-y-2 gap-x-4 w-11/12 my-4 space-y-0">
                        <!-- <li class="list-disc" v-for="n in 12" :key="n">Air Conditioning</li> -->
                        <div class="" v-for="n of 12" :key="n">
                            <input id="amenity" type="checkbox" checked class="mr-1 w-3 h-3 accent-orange-600 text-white">
                            <label for="amenity" class="text-gray-500">Air Conditioning</label>
                        </div>
                        
                    </div>
                </div>

                <div class="my-8">
                    <h3 class="pl-1 border-l-2 border-orange-400 text-lg font-medium">Location</h3>
                    <iframe class="my-4 h-80 w-full" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3909.013908283856!2d104.8808949142562!3d11.550859791798853!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x310951add5e2cd81%3A0x171e0b69c7c6f7ba!2sPasserelles%20Num%C3%A9riques%20Cambodia%20(PNC)!5e0!3m2!1sen!2skh!4v1583125279177!5m2!1sen!2skh" frameborder="0"> </iframe>
                </div>
                
                <div class="my-8">
                    <h3 class="pl-1 border-l-2 border-orange-400 text-lg font-medium">Floor Plans</h3>
                    <floor-plan />
                </div>

                <div class="my-8">
                    <h3 class="pl-1 border-l-2 border-orange-400 text-lg font-medium">Comments Reviews</h3>
                    <comment-card />
                    <comment-card />
                </div>
                
            </div>
        </div>

        <div class="">
            <agent-profile />

            <div class="shadow p-4 mt-5">
                <h3 class="pl-1 border-l-2 border-orange-400 text-lg font-medium">Write a Review</h3>
                <textarea class="border my-3 w-full p-1" placeholder="Comment" name="" id="" cols="30" rows="3"></textarea>
                <button class="bg-orange-600 text-white py-2 px-3 rounded">Post Comment</button>
            </div>
        </div>
      </div>
</section>
</template>

<script>
import AgentProfile from '~/components/AgentProfile.vue'
import Feature from '~/components/Feature.vue'
import MainHeader from '~/components/MainHeader.vue'
import PropertyInfoDetail from '~/components/PropertyInfoDetail.vue'
export default {
    components: { MainHeader, AgentProfile, PropertyInfoDetail, Feature },
    layout: 'Navigation',
}
</script>

<style>

</style>