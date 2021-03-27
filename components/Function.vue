<template>
  <div class="container">
    <img width="130px" src="https://globaleducationcoalition.unesco.org/uploads/222_Microbit_Educational_Foundation_color_logo_L1JPej.png?v=drqPpPus0q06Il2aCFAaocVL7eS295yXh0xY9eWkvJ0">
  </div>
</template>

<script>
export default {
  name: 'Function'
}
</script>

<style scoped>
  .container{
    background-color: #fff;
    border: 1px solid;
    width: 230px;
    height: 230px;
    display: flex;
    align-items: center;
    justify-content: center;
    transition: all 240ms ease-out;
  }
  .container:hover{
    cursor: pointer;
    transform: translateY(-15px);
    box-shadow: 3px 3px 4px rgba(0, 0, 0, 0.3);
  }
</style>
