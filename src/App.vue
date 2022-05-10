<template>
  <div>
    <SignupForm></SignupForm>
  </div>
</template>

<script>
import SignupForm from "@/components/SignupForm";
export default {
  name: 'App',
  components: {
    SignupForm
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
body{
  margin: 0;
  background: #eee;
}
</style>
