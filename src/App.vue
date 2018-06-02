<template>
  <div id="app">
    <login-form></login-form>
  </div>
</template>

<script>
import LoginForm from './components/LoginForm.vue';
export default {
  name: 'app',
  components:{
    LoginForm,
  },
  data () {
    return {
      
    }
  }
}
</script>

<style lang="scss">
@import './assets/css/style.scss';
</style>
