<template>
    <main>
        <h1>Integration: {{$route.query.id}}</h1>
    </main>
</template>

<script>
export default {

}
</script>

<style scoped>
main{
    width: 100%;
    display: flex;
    flex-direction: column;
    padding: 0 1em;
    align-items: flex-start;
}
h1{
    font-family:'Segoe UI', sans-serif;
    font-size: 35px;
}
</style>
