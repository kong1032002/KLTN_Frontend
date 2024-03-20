<script lang="ts" setup></script>

<template>
  <div>
    <div class="hidden md:block bg-white rounded-full px-4 py-2 border left-1/2 transform -translate-x-1/2  mt-4 fixed">
      <div class="button-group rounded-full overflow-hidden flex space-x-2">
        <button class="flex items-center justify-center hover:bg-slate-400 active:bg-slate-500 px-3 py-2 rounded">
          <Icon name="fa6-solid:house" />
          <span class="ml-1">Home</span>
        </button>
        <button class="flex items-center justify-center hover:bg-slate-400 active:bg-slate-500 px-3 py-2 rounded">
          <Icon name="fa6-solid:hourglass-empty" />
          <span class="ml-1">Predict</span>
        </button>
        <button class="flex items-center justify-center hover:bg-slate-400 active:bg-slate-500 px-3 py-2 rounded">
          <Icon name="fa6-solid:hourglass-empty" />
          <span class="ml-1">Early Predict</span>
        </button>
        <button class="flex items-center justify-center hover:bg-slate-400 active:bg-slate-500 px-3 py-2 rounded">
          <Icon name="fa6-solid:hourglass-empty" />
          <span class="ml-1">About</span>
        </button>
      </div>
    </div>
    <slot />
  </div>
</template>

<style scoped></style>
