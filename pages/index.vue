<template>
  <div>
    <h3>Select an integration:</h3>
  <div class="utilities-container">
    <div v-for="app in apps" :key="app">
      <Function v-bind:app="app"/>
    </div>
  </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      apps: [{ image: 'https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg', id: 'firebase' },
        { image: 'https://www.vectorlogo.zone/logos/google_cloud/google_cloud-icon.svg', id: 'google-cloud' },
        { image: 'https://upload.vectorlogo.zone/logos/wolframalpha/images/565aee38-9660-487b-b267-175cb1dac863.svg', id: 'wolphram-alpha' },
        { image: 'https://cdnjs.cloudflare.com/ajax/libs/simple-icons/4.13.0/github.svg', id: 'github' },
        { image: 'https://www.vectorlogo.zone/logos/mongodb/mongodb-icon.svg', id: 'mongoDB' }]
    }
  }
}
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
