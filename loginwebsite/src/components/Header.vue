<template>
    <div class="header">
        <h1>{{ title }}</h1>
    </div>

</template>

<script>
    export default {
      props: ['title']
  }

</script>

<style scoped>
    .header{
        width: 100%;
        background-color: rgba(255, 255, 255, 0.1);
        box-shadow: 0 5px 20px black;
        position: absolute;
        height: 50px;
        border-radius: 0 0 25px 25px;
        display: flex;
        align-items: center;
        justify-content: center;
        color: black;
    }
    h1{
        font-size: 2rem;
        letter-spacing: 10px;
        text-shadow: 5px 5px 10px black;
    }
</style>