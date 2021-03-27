<template>
  <div>
    <h3>Select a functionality</h3>
  <div class="utilities-container">
    <div v-for="i in 20" :key="i">
      <Function/>
    </div>
  </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@200;300;400;500;600&display=swap');

  h3{
    margin: 30px 0;
    font-family: "Inter", sans-serif;
    width: 100%;
    text-align: center;
    font-size: 40px;
    font-weight: bold;
  }
  .utilities-container{
    width: 100%;
    display: grid;
    justify-content: center;
    grid-template-columns: repeat(5, 230px);
  }
</style>
