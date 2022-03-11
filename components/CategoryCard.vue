<template>
  <div class=" p-6 my-4">
      <h1 class="text-lg font-bold">{{ data.title }}</h1>
      <hr class="my-3">
      <div class="flex justify-between text-gray-500" v-for="subTitle of data.items" :key="subTitle.type">
            <div class="">
                <input type="checkbox" :id="subTitle.type" name="vehicle1" value="Bike">
                <label :for="subTitle.type"> {{ subTitle.type }}</label>
            </div>
            <p>{{ subTitle.quanlity }}</p>
        </div>
  </div>
</template>

<script>
export default {
    props: ['data']

}
</script>

<style>

</style>