<template>
    <section>
        <main-header :title="'FAQ'" :subTitle="'FAQ'" />
        <div class="w-8/12 mx-auto my-10">
            <div class="text-center">
                <span
                    class="mx-auto inline-block rounded-full px-3 py-1 text-sm font-semibold bg-orange-300 text-white mr-2 mb-2">FAQ</span
                >
                <h1 class="text-4xl font-bold">Frequently Asked Questions</h1>
            </div>
            <div class="my-10 shadow p-10">
                <faq-card v-for="n of 8" :key="n" />
            </div>
        </div>
    </section>
</template>

<script>
import FaqCard from '~/components/FaqCard.vue'
import MainHeader from '~/components/MainHeader.vue'
export default {
  components: { MainHeader, FaqCard },
    layout: 'Navigation',
    data(){
        return{
            isShow: false,
        }
    }
}
</script>

<style>

</style>