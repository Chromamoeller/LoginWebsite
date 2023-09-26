<template>
    <div class="lable">
        <label for="username">Username</label>
        <input type="text" id="username" name="username" placeholder="">
    </div>
</template>
  
<script>
export default {

}
</script>
<style scoped>
.lable {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin-top: 50px;

}

label {
    font-size: 23px;
    font-weight: bold;
    margin-left: 20px;
}

input {
    margin-top: 20px;
    font-size: 23px;
    max-width: 300px;
    margin-left: 20px;
    text-align: center;
    border-radius: 16px;
    border-color: rgba(240, 240, 240, 0.5);
    background-color: transparent;
    box-shadow: 8px 8px 8px 5px rgba(0, 0, 0, 0.3);
}
</style>