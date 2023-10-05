<script setup lang="ts">

</script>

<template>
  <div class="container mx-auto p-2">
    <div class="bg-[#EDEDED] rounded-xl">
      <!-- Phần đầu -->
      <div>
        <!-- Hàng 1 -->
        <div class="flex">
          <div class="w-[220px]">
            <label class="text-[24px] me-2 flex justify-end font-medium ">テンプレート選択</label>
          </div>
          <div class="flex space-x-5">
            <select class="select border border-black rounded-none	h-[37px] w-full">
              <option disabled selected>Pick the best JS framework</option>
              <option>Svelte</option>
              <option>Vue</option>
              <option>React</option>
            </select>
            <label class="text-[24px] font-medium">テンプレート登録</label>
            <div class="h-[37px] w-[124px] border space-x-3 border-black bg-white flex items-center">
              <label class="ps-4 text-[24px]">登録</label>
              <input type="checkbox" class="h-[25px] w-[25px]">
            </div>
          </div>
        </div>
        <!-- Hàng 2 -->
        <div class="flex">
          <div class="w-[220px]">
            <label class="text-[24px] me-2 flex justify-end">送付先</label>
          </div>
          <div>
            <textarea class="w-[908px] h-[50px] overflow-y-scroll	border border-black p-2">
    </textarea>
          </div>
        </div>
        <!-- Hàng 3 -->
        <div class="flex">
          <div class="w-[220px]">
            <label class="text-[24px] me-2 flex justify-end font-medium">タイトル</label>
          </div>
          <div>
            <input type="text" class="h-[50px] p-2 border border-black w-full">
          </div>
        </div>
        <!-- Hàng 4 -->
        <div class="flex">
          <div class="w-[220px]">
            <label class="me-2 text-[24px] flex justify-end">本文</label>
          </div>
          <div>
            <textarea class="h-full w-[908px] overflow-y-scroll border border-black p-2"></textarea>
          </div>
        </div>
        <!-- Hàng 5 -->
        <div class="flex">
          <div class="w-[220px]">
            <label class="me-2 flex justify-end font-medium">添付ファイル</label>
          </div>
          <div>
            <textarea class="h-[50px] w-[908px] overflow-y-scroll  border border-black p-2"></textarea>
          </div>
          <div class="w-[100px]">
            <label class="px-3 text-[24px] text-[#139ff3] font-bold">参照</label>
          </div>
        </div>
      </div>
    </div>
    <!-- Phần thân -->
  </div>

  <!-- Nút -->
  <div class="flex justify-center space-x-[150px] my-[50px] h-[200px]">
    <button class="w-[236px] h-[50px] bg-[#EDEDED] text-[24px]">送信内容確認</button>
    <button class="w-[236px] h-[50px] bg-[#EDEDED] text-[24px]">戻る</button>
  </div>
</template>

<style scoped></style>
