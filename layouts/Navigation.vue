<template>
  <section>
      <div class="align-center grid grid-cols-3 gap-4 py-3 z-10 shadow bg-white sticky top-0">
            <div class="flex justify-center align-middle">
                <img src="../static/121-1217432_black-and-white-house-vector-png-png-download.png" class="w-28" alt="">
            </div>
            <nav class="">
                <ul class="flex justify-around pt-3">
                    <nuxt-link to="/"><li class="cursor-pointer font-bold text-sky-900 hover:text-orange-600">Home</li></nuxt-link>
                    <nuxt-link to="/properties"><li class="cursor-pointer font-bold text-sky-900 hover:text-orange-600">Properties</li></nuxt-link>
                    <nuxt-link to="/blog"><li class="cursor-pointer font-bold text-sky-900 hover:text-orange-600">Blog</li></nuxt-link>
                    <nuxt-link to="/aboutus"><li class="cursor-pointer font-bold text-sky-900 hover:text-orange-600">About Us</li></nuxt-link>
                    <nuxt-link to="/contact"><li class="cursor-pointer font-bold text-sky-900 hover:text-orange-600">Contact</li></nuxt-link>
                </ul>
            </nav>
            <div class="pt-3">
                <button class="shadow py-1 px-3 mx-2 text-orange-600">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"></path></svg>
                </button>
                <button class="shadow py-1 px-3 mx-2 text-orange-600">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z"></path></svg>
                </button>
                <button class="shadow py-1 px-3 mx-2 text-orange-600">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path></svg>
                </button>
            </div>
      </div>
      <Nuxt />
      
      <footer class="mt-16 h-96 bg-slate-800 relative">
          <h1>d</h1>
            <div class=" footer-card  h-28 bg-orange-600 w-8/12 px-8 mx-auto flex items-center justify-between">
                <div class="">
                    <h1 class="text-white text-3xl font-bold pb-3">Looking for a dream home?</h1>
                    <h3 class="text-white">We help you make the dream of new house a reality</h3>
                </div>
                <button class="shadow py-4 px-6 w-2/12 flex bg-white text-orange-600 ">
                    <span>Know More</span>
                    <svg class="w-6 h-6 pt-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg>
                </button>
            </div>
            <div class="grid grid-cols-6 gap-4 w-8/12 mx-auto mt-10">
                <div class="col-span-2">
                   <h1 class="text-white font-bold mb-4">About Us.</h1>
                   <p class="text-white text-sm">Lorem ipsum dolor sit amet consectetur adipisicing elit. Qui repudiandae ad odio hic dolorum tempora ea inventore possimus et blanditiis. Tempora necessitatibus nostrum nobis consequuntur. Tempora necessitatibus nostrum nobis consequuntur.</p>
                    <div class="flex mt-10">
                        <img src="https://www.svgrepo.com/show/111202/facebook.svg" class="w-8 mx-1" alt="">
                        <img src="https://www.svgrepo.com/show/111199/instagram.svg" class="w-8 mx-1" alt="">
                        <img src="https://www.svgrepo.com/show/157815/twitter.svg" class="w-8 mx-1" alt="">
                        <!-- <img src="https://www.pinterest.com/" class="w-8" alt=""> -->
                    <svg class="w-9 h-9 text-white bg-red-600 p-2 rounded-full font-bold mx-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M0 12c0 5.123 3.211 9.497 7.73 11.218-.11-.937-.227-2.482.025-3.566.217-.932 1.401-5.938 1.401-5.938s-.357-.715-.357-1.774c0-1.66.962-2.9 2.161-2.9 1.02 0 1.512.765 1.512 1.682 0 1.025-.653 2.557-.99 3.978-.281 1.189.597 2.159 1.769 2.159 2.123 0 3.756-2.239 3.756-5.471 0-2.861-2.056-4.86-4.991-4.86-3.398 0-5.393 2.549-5.393 5.184 0 1.027.395 2.127.889 2.726a.36.36 0 0 1 .083.343c-.091.378-.293 1.189-.332 1.355-.053.218-.173.265-.4.159-1.492-.694-2.424-2.875-2.424-4.627 0-3.769 2.737-7.229 7.892-7.229 4.144 0 7.365 2.953 7.365 6.899 0 4.117-2.595 7.431-6.199 7.431-1.211 0-2.348-.63-2.738-1.373 0 0-.599 2.282-.744 2.84-.282 1.084-1.064 2.456-1.549 3.235C9.584 23.815 10.77 24 12 24c6.627 0 12-5.373 12-12S18.627 0 12 0 0 5.373 0 12"></path></svg>
                        
                        
                    </div>
                </div>
                <div class="...">
                    <h1 class="text-white font-bold mb-4">Menu</h1>
                    <ul class="text-white">
                        <nuxt-link to="/"><li class="hover:underline hover:underline-offset-1">Home</li></nuxt-link>
                        <nuxt-link to="/properties"><li class="hover:underline hover:underline-offset-1">Properties</li></nuxt-link>
                        <nuxt-link to="/blog"><li class="hover:underline hover:underline-offset-1">Blog</li></nuxt-link>
                        <nuxt-link to="/aboutus"><li class="hover:underline hover:underline-offset-1">About Us</li></nuxt-link>
                        <nuxt-link to="/contact"><li class="hover:underline hover:underline-offset-1">Contact</li></nuxt-link>
                    </ul>
                </div>
                <div class="...">
                    <h1 class="text-white font-bold mb-4">Help?</h1>
                    <ul class="text-white">
                        <nuxt-link to="/faq"><li class="hover:underline hover:underline-offset-1">FAQ</li></nuxt-link>
                        <li>Tern & Conditions</li>
                        <li>Reporting</li>
                        <li>Support Policy</li>
                        <li>Privacy</li>
                    </ul>
                </div>
                <div class="col-span-2">
                    <!-- <div class="flex justify-center"> -->
                        <img src="../static/121-1217432_black-and-white-house-vector-png-png-download.png" class="w-28" alt="">
                    <!-- </div> -->
                    <p class="text-sm text-white">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ea, accusantium.</p>
                    <div class="flex py-4 text-white">
                        <svg class="w-6 h-6 text-sm" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path></svg>
                        <p class="text-sm">Phnom Penh, Cambodia</p>
                    </div>

                    <div class="bg-white p-2 flex justify-between mt-5">
                        <input type="text" class="outline-none p-3" placeholder="Enter email address">
                        <button class="bg-orange-600 p-3 text-white">Subscribe</button>
                    </div>
                </div>
            </div>
      </footer>
  </section>
</template>

<script>
export default {

}
</script>

<style scoped>
.footer-card{
    margin-top: -70px;

}
footer{
    z-index: 2;
}
</style>