<script setup lang="ts">

</script>

<template>
  <div class="container mx-auto p-2">
    <!-- Phần đầu -->
    <div class="bg-[#EDEDED] h-[671px] w-[1248px]">
      <!-- Hàng 1 -->
      <div class="flex justify-evenly mx-5">
        <label>テンプレート選択</label>
        <select name="" id=""></select>
        <label>テンプレート登録</label>
        <div class="h-[37px] w-[124px] flex border border-black bg-white" >
          <p>登録</p>
          <input type="checkbox" name="" id="">
        </div>
      </div>
      <!-- Hàng 2 -->
      <div class="flex">
        <label>送付先</label>
        <textarea class="h-[50px] w-[908px] overflow-y-scroll"></textarea>
      </div>
      <!-- Hàng 3 -->
      <div>
        <label>タイトル</label>
        <input type="text" class="h-[37px] w-[908px]">
      </div>
      <!-- Hàng 4 -->
      <div>
        <label>本文</label>
        <textarea class="h-[298px] w-[908px] overflow-y-scroll"></textarea>
      </div>
      <!-- Hàng 5 -->
      <div class="flex">
        <label>添付ファイル</label>
        <textarea class="h-[50px] w-[908px] overflow-y-scroll"></textarea>
        <p class="text-[#17ACE3] h-[21px] w-[57px]">参照</p>
      </div>
    </div>
    <!-- Phần thân -->
    <div class="h-full">
      <!-- Nút -->
      <div class="flex justify-evenly my-[50px]">
        <button class="w-[236px] h-[50px] bg-[#EDEDED]">送信内容確認</button>
        <button class="w-[236px] h-[50px] bg-[#EDEDED]">戻る</button>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
