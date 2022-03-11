<template>
  <section>
    <main-header :title="'Properties List'" :subTitle="'Properties List'" />

    <div class="grid grid-cols-6 gap-4 w-9/12 mx-auto my-16 pb-16">
        <div class=" col-span-2">
            <h1 class="text-2xl font-bold">Advance Information</h1>
            <p class="text-xs">About 9,620 results</p>
            <div class="shadow mt-7 p-6">
                <category-card v-for="filter of filters" :key="filter.title" :data="filter" />
            </div>
        </div>
        <div class="col-span-4">
            <div class="flex justify-end mb-6">
                <div class="flex items-center justify-end w-6/12">
                <label for="sort">Sort By: </label>
                <select name="sort" id="sort" class="border-2 rounded-md p-2 w-6/12 m-1">
                    <option value="volvo">Volvo</option>
                    <option value="saab">Saab</option>
                    <option value="mercedes">Mercedes</option>
                    <option value="audi">Audi</option>
                </select>
                <button class="p-2 shadow rounded-md m-1" :class="!showRow ? 'bg-orange-200' : 'bg-gray-100'">
                    <img class="w-6 h-6" src="https://www.svgrepo.com/show/239227/layout.svg" @click.stop="showRow = false" alt="">
                </button>
                <button class="p-2 shadow rounded-md bg-gray-100 m-1" @click.stop="showRow = true"  :class="showRow ? 'bg-orange-200' : 'bg-gray-100'">
                    <img class="w-6 h-6" src="https://www.svgrepo.com/show/239232/layout-edit-tools.svg" alt="">
                </button>
            </div>
            </div>
            <div class="" v-if="showRow">
                <row-card  v-for="n of 4" :key="n" />
            </div>
            <div class="grid grid-cols-2 gap-4" v-else >
                <card v-for="n of 4" :key="n" />
            </div>


           <pagination />
        </div>
    </div>

  </section>
</template>

<script>
import Card from '~/components/Card.vue'
import CategoryCard from '~/components/CategoryCard.vue'
import RowCard from '~/components/RowCard.vue'
import MainHeader from '~/components/MainHeader.vue'
import Pagination from '~/components/Pagination.vue'
export default {
  components: { Card, CategoryCard, RowCard, MainHeader, Pagination },
    layout: 'Navigation',
    data(){
        return{
            showRow: false,
            filters: [
                {
                    title: 'Category',
                    items: [
                        {
                            type: 'Buying',
                            quanlity: 1234
                        },
                        {
                            type: 'Renting',
                            quanlity: 1234
                        },
                        {
                            type: 'Selling',
                            quanlity: 1234
                        },
                    ]
                },
                {
                    title: 'Property type',
                    items: [
                        {
                            type: 'House',
                            quanlity: 1234
                        },
                        {
                            type: 'Single Family',
                            quanlity: 1234
                        },
                        {
                            type: 'Apartment',
                            quanlity: 1234
                        },{
                            type: 'Office Villa',
                            quanlity: 1234
                        },{
                            type: 'Luxary Home',
                            quanlity: 1234
                        },{
                            type: 'Studio',
                            quanlity: 1234
                        },
                    ]
                },
                //  {
                //     title: 'Amenities',
                //     items: [
                //         {
                //             type: 'Dishwasher',
                //             quanlity: 1234
                //         },
                //         {
                //             type: 'Floor Coverings',
                //             quanlity: 1234
                //         },
                //         {
                //             type: 'Internet',
                //             quanlity: 1234
                //         },{
                //             type: 'Build Wardrobes',
                //             quanlity: 1234
                //         },{
                //             type: 'Supermarket',
                //             quanlity: 1234
                //         },{
                //             type: 'Kids Zone',
                //             quanlity: 1234
                //         },
                //     ]
                // },
                {
                    title: 'Price Renge',
                    items: [
                        {
                            type: 'Low Budget',
                            quanlity: 1234
                        },
                        {
                            type: 'Medium',
                            quanlity: 1234
                        },
                        {
                            type: 'High Budget',
                            quanlity: 1234
                        },
                    ]
                },
            ],
           
        }
    },
    
}
</script>

<style>

</style>