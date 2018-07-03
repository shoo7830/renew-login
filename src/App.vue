<template>
  <div id="app">
    <form>
      <section>
        <svg-area></svg-area>
        <login-form></login-form>
      </section>
    </form>
    
  </div>
</template>

<script>
import SvgArea from './components/SvgArea.vue';
import LoginForm from './components/LoginForm.vue';

export default {
  name: 'app',
  components:{
    LoginForm,
    SvgArea
  },
  data () {
    return {
      x: 0,
      y: 0
    }
  },

  methods() {
    
  }
}
</script>

<style lang="scss" src="./assets/css/style.scss"></style>
