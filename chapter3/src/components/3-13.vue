<template>
  <div>
    <button @click="increment">더하기</button>
  </div>
</template>
<script>
  import store from  'src/stores';
  export default {
    methods: {
      increment () {
        store.commit('INCREMENT', 2)
      }
    }
  }
</script>
