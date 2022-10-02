<template>
  <div>
    <h1 class="text-2xl text-center font-bold">This is the user page.</h1>
    <div class="badge">Testing</div>
    <p class="bg-red-300">
      <a
        target="_blank"
        href="https://tailwindcss.nuxtjs.org/getting-started/setup"
      >
        After taking official doc as reference. Somehow the color settings work.
      </a>
    </p>
  </div>
</template>
<script>
export default {
  name: "UserPage",
};
</script>

<style lang="postcss" scoped>
.badge {
  @apply bg-gray-200 rounded-full inline-block font-semibold;
  &:hover {
    @apply bg-gray-300;
  }
}
</style>
