<template>
  <section>
      <main-header :title="'Contact Us'" :subTitle="'Contact Us'" />

      <div class="shadow w-8/12 mx-auto my-16 border rounded-md p-10 grid grid-cols-7 gap-4">
        <div class="col-span-3 ">
            <h1 class="text-4xl font-bold">Fell Free to contact us for any query.</h1>
            <div class="mt-14">
                <div class="flex items-center">
                    <svg class="w-14 h-14 p-4 rounded-full bg-orange-600 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path></svg>
                    <div class="ml-2">
                        <p class="text-base font-semibold">Phone Number:</p>
                        <p class="text-sm">Head office: 097 491 1250</p>
                    </div>
                </div>
            </div>
            <div class="mt-6">
                <div class="flex items-center">
                    <svg class="w-14 h-14 p-4 rounded-full bg-orange-600 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 12a4 4 0 10-8 0 4 4 0 008 0zm0 0v1.5a2.5 2.5 0 005 0V12a9 9 0 10-9 9m4.5-1.206a8.959 8.959 0 01-4.5 1.207"></path></svg>
                    <div class="ml-2">
                        <p class="text-base font-semibold">Mail Address:</p>
                        <p class="text-sm">somphors@mango-byte.com</p>
                    </div>
                </div>
            </div>
            <div class="mt-6">
                <div class="flex items-center">
                        <svg class="w-14 h-14 p-4 rounded-full bg-orange-600 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path></svg>                    <div class="ml-2">
                        <p class="text-base font-semibold">Office Address: Number:</p>
                        <p class="text-sm">Koh Pich Phnom Penh 120101 Cambodia</p>
                    </div>
                </div>
            </div>
        </div>
        <div class="col-span-4 mt-4">
            <div class="grid grid-cols-2 gap-4">
                <div class="flex bg-gray-100 px-2 py-1 ">
                    <input type="text" placeholder="First Name" class="w-96 outline-none border-0 bg-gray-100">
                    <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"></path></svg>
                </div>

                <div class="flex bg-gray-100 px-2 py-1 ">
                    <input type="text" placeholder="Last Name" class="w-96 outline-none border-0 bg-gray-100">
                    <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"></path></svg>
                </div>
            </div>
            <div class="grid grid-cols-2 gap-4 mt-6">
                <div class="flex bg-gray-100 px-2 py-1 ">
                    <input type="text" placeholder="Email" class="w-96 outline-none border-0 bg-gray-100">
                    <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                </div>

                <div class="flex bg-gray-100 px-2 py-1 ">
                    <input type="text" placeholder="Phone Number" class="w-96 outline-none border-0 bg-gray-100">
                    <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path></svg>
                </div>
            </div>
            <div class="grid grid-cols-1 gap-4 mt-6 ">
                <select name="cars" id="cars" class="bg-gray-100 p-2" placeholder="Choose property">
                    <option disabled value="volvo">Volvo</option>
                    <option value="saab">Choose property</option>
                    <option value="mercedes">Mercedes</option>
                    <option value="audi">Audi</option>
                </select>

            </div>
            <div class="grid grid-cols-1 gap-4 mt-6">
                <textarea name="" class="bg-gray-100 p-2" placeholder="Message" id="" cols="30" rows="5"></textarea>

            </div>
             <button class="shadow py-4 mt-6 px-6 flex bg-orange-600 text-white ">
                    <span>Send Message</span>
                    <svg class="w-6 h-6 pt-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg>
                </button>
        </div>
      </div>

        <div class="">
      <iframe class="map h-96" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3909.013908283856!2d104.8808949142562!3d11.550859791798853!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x310951add5e2cd81%3A0x171e0b69c7c6f7ba!2sPasserelles%20Num%C3%A9riques%20Cambodia%20(PNC)!5e0!3m2!1sen!2skh!4v1583125279177!5m2!1sen!2skh" width="100%" frameborder="0"></iframe>

        </div>
  </section>
</template>

<script>
import MainHeader from '~/components/MainHeader.vue'
import RowCard from '~/components/RowCard.vue'
export default {
  components: { RowCard, MainHeader },
  layout: 'Navigation',
}
</script>

<style scoped>
    .map{
        margin-bottom: -67px;
        z-index: -11;
    }
</style>