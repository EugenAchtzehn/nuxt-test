<template>
  <div>動態路由, Dynamic~</div>
</template>

<script>
export default {
  created () {
    // console.log(this.$route.params.id)
    alert(this.$route.params.id);
    // 可以在瀏覽器進入 http://localhost:3000/example/{anyParams}
  },
}
</script>
