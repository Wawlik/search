<template>
  <div id="app">
    <header>
      <div class="logo">
        <img src="../static/logo.png" alt="Logo">
      </div>
      <search></search>
    </header>
    <main>
      <result></result> 
    </main>
  </div>
</template>

<script>
import Search from '../components/Search.vue'
import Result from '../components/Result.vue'

export default {
  name: 'app',
  components: { Search, Result }
  
}
</script>
<style src="../static/style.css"></style>