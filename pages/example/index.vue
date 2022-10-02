<template>
  <div>
    <h2>index.vue</h2>
    <p>path "/example" 會進入這頁</p>
    <p class="bg-blue-300 font-bold">
      Q:
      <br />
      不確定原因，但感覺某些 TailwindCSS 的顏色設定在本專案中無法套用，像是
      background-color 和 border-color...。
      <br />
      但很奇怪地，文字顏色卻又同時可以被設定。
    </p>
    <p class="bg-pink-200 font-bold">
      A:
      <br />
      答案可能很簡單，就是在 Nuxt 中的 TailwindCSS
      還沒有支援那麼多樣化的顏色設定。
      <br />
      可能是版本問題不相容，因為使用基礎顏色的 class 是可以成功調整的。
    </p>
  </div>
</template>
