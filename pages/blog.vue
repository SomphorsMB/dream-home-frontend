<template>
    <section>
        <main-header :title="'Blog'" :subTitle="'Blog'" />
        <div class="w-9/12 mx-auto mt-10"> 
            
            

            <div class="grid grid-cols-3 gap-4 mb-16 pb-16">
                <div class="col-span-2 grid grid-cols-1 gap-4">
                    <blog-card v-for="n in 3" :key="n" />

                    <pagination />
                </div>

                <div class="">
                    <div class="mt-10 p-4 bg-white shadow rounded-lg">
                        <h3 class="pl-1 border-l-2 border-orange-400 text-lg font-medium">Search Bar</h3>
                        <div class="border rounded-sm flex items-center  mx-auto my-2">
                            <input type="text" placeholder="Search..." class=" w-11/12 p-2">
                            <div class="bg-orange-500 py-2 px-3">
                                <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path></svg>
                            </div>
                        </div>
                    </div>

                    <div class="mt-5 p-4 bg-white shadow rounded-lg">
                        <h3 class="pl-1 border-l-2 border-orange-400 text-lg font-medium">Latest Properties</h3>
                        <div class="my-3 flex items-end" v-for="m in 3" :key="m">
                            <img class="w-20 h-20" src="https://assets.entrepreneur.com/content/3x2/2000/1604135072-webaliser--TPTXZd9mOo-unsplash.jpg" alt="">
                            <div class="mx-2 w-8/12">
                                <h3 class="text-orange-400">$ 90,000</h3>
                                <p>Neue Dimensinen im Schragdach</p>
                            </div>
                        </div>
                    </div>

                    <div class="mt-5 p-4 bg-white shadow rounded-lg">
                        <h3 class="pl-1 border-l-2 border-orange-400 text-lg font-medium">Top Categories</h3>
                        <div class="bg-orange-100 text-orange-600 p-2 my-3 " v-for="k in 4" :key="k">
                            Apartment (120)
                        </div>
                       
                    </div>
                    
                     <div class="mt-5 p-4 bg-white shadow rounded-lg">
                        <h3 class="pl-1 border-l-2 border-orange-400 text-lg font-medium">Latest Blogs</h3>
                        <div class="my-3 flex items-end" v-for="m in 3" :key="m">
                            <img class="w-20 h-20" src="https://cdn.pixabay.com/photo/2018/03/18/13/56/architecture-3236871__340.jpg" alt="">
                            <div class="mx-2 w-8/12">
                                <span class="flex items-center pr-2 text-xs">
                                    <svg class="w-4 h-4 text-orange-400 mr-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"></path></svg>
                                    <span>Feb 28, 2022</span>
                                </span>
                                <p>Neue Dimensinen im Schragdach</p>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </div>
    </section>
</template>

<script>
import BlogCard from '~/components/BlogCard.vue'
import MainHeader from '~/components/MainHeader.vue'
import Pagination from '~/components/Pagination.vue'
export default {
    components: { MainHeader, BlogCard, Pagination },
    layout: 'Navigation',
}
</script>

<style>

</style>