<script setup>
import Group from '../components/Group.vue';
import Head from '../components/Tup.vue';
</script>

<template>
  <div class="bg-white w-3/5 m-auto rounded-xl shadow-xl shadow-grey-200 mt-20">
    <Head />

    <div class="p-10">
      <div class="flex justify-between items-center mb-10">
        <h1 class="text-3xl font-bold">Все аксессуары</h1>
        <div class="flex items-center gap-4">
          <select
            class="py-2 px-3 border border-gray-200 focus:border-gray-400 rounded-md focus:outline-none"
          >
            <option value="name">По названию</option>
            <option value="price">По цене (дешевые)</option>
            <option value="price">По цене (дорогие)</option>
          </select>
          <div class="relative">
                <div class="absolute inset-y-0 left-0 pl-3 flex items-center pointer-events-none">
              <img src="/Poisk.svg" />
            </div>
          </div>
        </div>
      </div>

      <div class="grid grid-cols-4 gap-10">
        <Group
          title="Ray bans rb3052 Aviator Green"
          price="5000"
          img="/sharkSwim/RayBanAviator.jpg"
        />
      </div>
      <div class="grid grid-cols-4 gap-10">
        <Group
          title="Ray bans rb3052 Aviator Green"
          price="25000000"
          img="/sharkSwim/RayBanAviator.jpg"
        />
      </div>
    </div>
    
  </div>
</template>
