<script lang="ts" setup></script>

<template>
  <div class="rounded-lg bg-white border overflow-hidden mx-40">
    <div class="flex">
      <div class="basis-1/2 p-5">
        <p class="text-center font-bold mb-3">Predict</p>
        <form class="grid grid-cols-3 gap-4">
          <label for="pair_id">Uniswap pair</label>
          <input id="pair_id" type="text" class="ml-3 border-2 rounded border-zinc-200 col-span-2">
          <label for="pair_id">Smart contract</label>
          <input id="pair_id" type="text" class="ml-3 border-2 rounded border-zinc-200 col-span-2">
          <div class="col-span-3 flex justify-center gap-3">
            <input type="submit" value="Predict"
              class="basis-1/4 border-sky-500 border-2 rounded hover:bg-sky-500 hover:text-white active:bg-sky-600 py-1">
            <input type="button" value="Early predict"
              class="basis-1/4 border-sky-500 border-2 rounded hover:bg-sky-500 hover:text-white active:bg-sky-600 py-1">
          </div>
        </form>
      </div>
      <div class="basis-1/2 bg-sky-600 p-5 text-white rounded-lg">
        <p class="text-center font-bold mb-3">Phương pháp 1</p>
        <p>
          Phương pháp dự đoán dựa trên toàn bộ lịch sử giao dịch, hoạt động của một smart contract trong một số ngày đầu
          tiên được
          đưa lên Uniswap
        </p>
        <p class="text-center font-bold mb-3">Dự đoán sớm</p>
        <p>
          Phương pháp dự đoán dựa trên những giao dịch, hoạt động của một smart contract trong một số ngày đầu tiên được
          đưa lên Uniswap
        </p>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
