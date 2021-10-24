<template>
    <div class="container">
        <p>checkbox</p>
        <p>type</p>
        <p>name</p>
        <p>price</p>
        <p>size</p>
    </div>
</template>


<script>
export default {
    name: 'Container',
}

</script>

<style scoped>

.container{
  border: 1px solid black;
  width: 19rem;
  height: 12rem;
  margin: 2rem;
}
p{
    display: block;
    align-items: center;
    justify-content: center;
}
</style>