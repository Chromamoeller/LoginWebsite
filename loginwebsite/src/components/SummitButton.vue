<template>
    <div class="lable">
        <button>
            <slot>{{ message }}</slot>
        </button>
    </div>
</template>

<script>
export default {
    props: {
        message: String
    }
}
</script>

<style scoped>
button {
    margin-top: 50px;
    width: 100px;
    height: 35px;
    border-radius: 20px;
    border-color: transparent;
    background-color: rgba(200, 200, 200, 0.5);
    font-size: 1.6rem;
    box-shadow: 5px 5px 5px rgba(0, 0, 0, 0.5);
}

button:hover {
    background-color: rgba(240, 240, 240, 0.8);
    cursor: pointer;
}

button:active {
    background-color: rgba(240, 240, 240, 0.2);

}
</style>