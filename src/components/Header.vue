<template>
  <div class="header">
      <h1>이선용</h1>
      <img :src="btn_close" alt="닫기">
  </div>
</template>

<script>
export default {
    data(){
        return{
            btn_close:require("../assets/icon-close.png")
        }
    }
}
</script>

<style>
    .header{
        display:flex;
        justify-content: space-between;
        align-content: center;
    }
</style>