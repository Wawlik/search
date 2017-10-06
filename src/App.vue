<template>
  <div id="app">
    <header>
      <div class="logo">
        <img src="https://i.imgur.com/WoCZlYa.png" alt="Logo">
      </div>
      <search></search>
    </header>
    <main>
      <result></result> 
    </main>
  </div>
</template>

<script>
import logo from '../static/logo.png'
import Search from '../components/Search.vue'
import Result from '../components/Result.vue'

export default {
  name: 'app',
  components: { Search, Result },
  data() {
    return { 
      logo 
    }
  }
}
</script>
<style src="../static/style.css"></style>