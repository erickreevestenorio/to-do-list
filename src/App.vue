<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>

    <div class="card w-2/5 bg-white rounded shadow-lg mx-auto p-10">
      <div class="">
        <div class="date">
          <strong>12</strong>
          <strong>Jan</strong>
          2019
        </div>
        <p>TUESDAY</p>
      </div>
      <router-view class="mt-10"/>
    </div>


    
  </div>
</template>
<script>
import './assets/styles/main.css'
export default {
  
}
</script>

<style>
  body {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    background: #E9E9E4;
  }
  .card {
    min-height: 400px;
  }
</style>
