<template>
  <div class="panel">
    <UsernameInputField />
    <PasswordInputField />
    <SummitButton message="Login" />

  </div>
</template>



<script>
import UsernameInputField from './UsernameInputField.vue'
import PasswordInputField from './PasswordInputField.vue'
import SummitButton from './SummitButton.vue'
export default {
  components: {
    UsernameInputField,
    PasswordInputField,
    SummitButton,
  }

}
</script>

<style scoped>
.panel {
  width: 300px;
  box-shadow: 5px 5px 5px rgba(0, 0, 0, 0.7);
  height: 400px;
  margin-top: 100px;
  background-color: rgba(221, 221, 221, 0.8);
  border-radius: 40px;
}
</style>
