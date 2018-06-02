<template>
  <div id="app">
    <form>
        <section>
            <div>
                <!-- SVG 영역 -->
            </div>
            <div class="input-group">
                <input type="text" placeholder="아이디">
            </div>
            <div class="input-group">
                <input type="password" placeholder="비밀번호">
            </div>
            <div class="input-group">
                <button class="submit-button">로그인</button>
            </div>
            
        </section>
    </form>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="scss">
@import './assets/css/style.scss';
</style>
