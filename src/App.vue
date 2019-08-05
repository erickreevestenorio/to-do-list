<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    
    <div class="card bg-white rounded shadow-lg mx-auto">
      <Header class="p-8"></Header>
      <div class="card-body p-8">
        
        <!-- <router-view class="px-10"/> -->
        <Todolist></Todolist>


      </div>
      <Footer></Footer>
    </div>


    
  </div>
</template>
<script>
import './assets/styles/main.css'

import Header from '@/components/Header.vue'
import Todolist from '@/views/Todolist.vue'
import Footer from '@/components/Footer.vue'
export default {
  components: { 
    Header,
    Todolist,
    Footer
  }
}
</script>

<style>
  body {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    background: #E9E9E4;
    color: #5D5D5D;
    font-family: 'Poppins', sans-serif;
  }
  .card {

    max-width: 400px;
  }
  .roboto {
    font-family: 'Roboto', sans-serif;
  }
  .card-body {
    min-height: 350px;
  }
  strong {
    font-weight: 550;
  }
</style>
