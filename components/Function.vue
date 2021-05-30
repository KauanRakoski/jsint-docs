<template>
  <NuxtLink :to="'\app?id=' + app.id" class="container">
    <img width="100px" :src="app.image">
  </NuxtLink>
</template>

<script>
export default {
  name: 'Function',
  props: {
    app: Object
  }
}
</script>

<style scoped>
  .container{
    background-color: rgb(245, 245, 245);
    border-radius: 5px;
    width: 180px;
    height: 180px;
    display: flex;
    align-items: center;
    justify-content: center;
    transition: all 240ms ease-out;
  }
  .container:hover{
    cursor: pointer;
    transform: translateY(-15px);
    box-shadow: 3px 3px 4px rgba(0, 0, 0, 0.14);
  }
</style>
