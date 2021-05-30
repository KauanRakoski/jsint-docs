<template>
    <header>
        <div class="logo">
            <img src="https://i.ibb.co/1n1QFwP/apibox.png">
            <h2>apibox docs</h2>
        </div>
    </header>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style scoped>
header{
    height: 80px;
    box-shadow: 1px 3px 5px rgba(0, 0, 0, .2);
    margin-bottom: 50px;
}
.logo{
    height: 80px;
    display: flex;
    align-items: center;
}
.logo img{
    transform: scale(0.4);
}
.logo h2{
 font-weight: 500;
}
</style>
