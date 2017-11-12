<template>
  <div id="nonpre">
    여기는 pre render가 되지 않은 페이지 입니다.

    <div>
      <router-link :to="{ name: 'Hello' }">홈으로 가기</router-link>
    </div>
  </div>
</template>

<script>

</script>

<style>

</style>