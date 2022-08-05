<template>
<div class="menu">
  <a v-for="작명 in 3" :key="작명">Home</a>
</div>
 <div>
    <h4>XX 원룸</h4>
    <p :style="스타일">{{price1}} 만원</p>
  </div>
  <div>
    <h4>XX 원룸</h4>
    <p>XX 만원</p>
  </div>
</template>

<script>

export default {
  name : 'App',
  data(){
    return {
      price1 : 60,
      스타일 : 'color:orange'
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
