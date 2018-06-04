<template>
  <div id="app">
    <form>
      <section>
        <login-form></login-form>
      </section>
    </form>
    
  </div>
</template>

<script>
import LoginForm from './components/LoginForm.vue';

export default {
  name: 'app',
  components:{
    LoginForm
  },
  data () {
    return {
      
    }
  }
}
</script>

<style lang="scss" src="./assets/css/style.scss"></style>
