<template>
  <div class="grid grid-cols-4 mx-auto gap-4 w-8/12  mt-10">
    <div class="shadow h-48 flex items-center justify-center" v-for="data of lists" :key="data.title">
        <div class="text-center">
                <!-- <svg class="w-16 h-16 text-orange-600 bg-orange-100 p-3 rounded-full mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"></path></svg> -->
                <div class="bg-orange-100 w-16 h-16 p-3 mx-auto rounded-full flex items-center justify-center">
                    <img :src="data.image" class="w-12" alt="">
                </div>
                <h1 class="text-2xl font-bold pb-1 pt-2">{{ data.title }}</h1>
            
            </div>
    </div>

    </div>
</template>

<script>
export default {
    data(){
        return{
            lists: [
                {
                    title:'Parking Space',
                    image: 'https://www.svgrepo.com/show/125/car.svg'
                },
                {
                    title:'Swimming Pool',
                    image: 'https://www.svgrepo.com/show/195971/swimming-pool.svg'
                },
                {
                    title:'Private Security',
                    image: 'https://cdn-icons.flaticon.com/png/512/735/premium/735721.png?token=exp=1645588370~hmac=142353ad0aa8746538a4acdd2d3f8628'
                },
                
                {
                    title:'Medicine Center',
                    image: 'https://www.svgrepo.com/show/25872/medicine.svg'
                },
                {
                    title:'Library Area',
                    image: 'https://www.svgrepo.com/show/245968/library-book.svg'
                },
                {
                    title:'King Size Bed',
                    image: 'https://www.svgrepo.com/show/195983/bed.svg'
                },
                {
                    title:'Smart Home',
                    image: 'https://www.svgrepo.com/show/270407/smart-home.svg'
                },
                {
                    title:"Kid's Playland",
                    image: 'https://www.svgrepo.com/show/231883/playground.svg'
                },
            ]
        }
    }
}
</script>

<style>

</style>