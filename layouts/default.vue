<script lang="ts" setup></script>

<template>
  <div class="">
    <div class="flex justify-center ">
      <div class="hidden lg:block bg-white rounded-full px-4 py-2 border mt-4 fixed shadow">
        <div class="button-group rounded-full overflow-hidden flex space-x-2">
          <button class="flex items-center overflow-hidden">
            <img src="./../assets/imgs/logo.jpg" class="h-11" alt="" srcset="">
            <span class="ml-1 font-bold">RugGuard</span>
          </button>
          <button class="flex items-center hover:bg-slate-400 active:bg-slate-500 px-3 py-2 rounded">
            <Icon name="fa6-solid:house" />
            <span class=" ml-1 font-semibold">Home</span>
          </button>
          <button class="flex items-center hover:bg-slate-400 active:bg-slate-500 px-3 py-2 rounded">
            <Icon name="fa6-solid:hourglass-empty" />
            <span class="ml-1 font-semibold">Predict</span>
          </button>
          <button class="flex items-center hover:bg-slate-400 active:bg-slate-500 px-3 py-2 rounded">
            <Icon name="fa6-solid:hourglass-empty" />
            <span class="ml-1 font-semibold">Early Predict</span>
          </button>
          <button class="flex items-center hover:bg-slate-400 active:bg-slate-500 px-3 py-2 rounded">
            <Icon name="fa6-solid:hourglass-empty" />
            <span class="ml-1 font-semibold">About</span>
          </button>
        </div>
      </div>
    </div>
    <div class="bg-gray-100 px-4">
      <slot />
    </div>
    <About />
  </div>
</template>

<style scoped>
.roboto {
  font-family: 'Roboto', sans-serif;
}
</style>
