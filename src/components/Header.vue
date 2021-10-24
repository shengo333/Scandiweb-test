<template>
    <div class="product_header">
        <h1> Product list </h1>
        <div class="product_header_options">
            <button> Add </button>
            <button> Delete </button>
        </div>
    </div>
</template>


<script>
export default {
    name: 'Header',
}
</script>

<style scoped>
    .product_header{
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-bottom: 1rem;
        margin-left: 2rem;
        margin-right: 2rem;
        border-bottom: 2px solid black;
    }
    h1{
          display: block;

    }
    .product_header_options{
        display: flex;
        justify-content: space-between;

    }
    button{
        height: 2rem;
        margin: 0 1rem;
    }

</style>
