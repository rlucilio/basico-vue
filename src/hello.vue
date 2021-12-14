<template>
  <div>
    <h1>nome</h1>
    <input type="text" v-model="nome" />
  </div>
</template>

<script>
export default {
  name: "hello-component",
  data: () => ({ nome: "Renan" }),
};
</script>

<style scoped>
    h1 {
        color: red;
    }
</style>