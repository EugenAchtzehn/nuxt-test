<template>
  <div>
    <h2>動態路由, Dynamic~</h2>
    <p>{{ this.$route.params.id }}</p>
  </div>
</template>

<script>
export default {
  created() {
    // alert(this.$route.params.id);
    // 可以在瀏覽器進入 http://localhost:3000/example/{anyParams}
  },
};
</script>
