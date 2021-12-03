<template>
    <div class="container">
        <input type="checkbox" id="checkbox">
        <p>{{product.type}}</p>
        <p>{{product.name}}</p>
        <p>{{product.price}}</p>
        <p>{{product.size}}</p>
    </div>
</template>


<script>
export default {
    name: 'Container',
    props: {
        product: Array,
    },
}

</script>

<style scoped>

.container{
  border: 1px solid black;
  width: 16rem;
  height: 8rem;
  margin: 2rem;
}
p{
    display: block;
    align-items: center;
    justify-content: center;
    padding: 0;
    margin: 0;
}
#checkbox{
    display: block;
    padding: 1rem;
    margin-top: 1rem;
    margin-left: 1.5rem;
}
</style>