<template>
  <div class="">
    <div class=" border rounded my-4 ">
        <div class="py-4 px-8 flex items-center justify-between font-medium hover:bg-orange-400 hover:text-white">
            <p>Is it possible ti purchase a home in MO with no money down ?</p>
            <div class="bg-gray-600 hover:cursor-pointer" @click.stop="isShow = !isShow">
                <svg v-if="!isShow" class="w-4 h-4 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6v6m0 0v6m0-6h6m-6 0H6"></path></svg>
                <svg v-else class="w-4 h-4 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20 12H4"></path></svg>
            </div>
        </div>
        <div class="text-gray-500 pb-4 px-8 w-[97%] text-base" v-if="isShow">
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Facilis sint quod ratione minus sit nihil quam rerum assumenda beatae et laborum, necessitatibus sapiente nostrum quas repellat esse nobis perferendis quidem provident quasi pariatur ullam totam voluptates! Quod facere ad in.
        </div>
    </div>
  </div>
</template>

<script>
export default {
    // props: ['isShow']
    data(){
        return{
            isShow: false,
        }
    }
}
</script>

<style>

</style>