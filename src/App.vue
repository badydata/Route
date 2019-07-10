<template>
  <div id="app"> 
    <router-link to="/home">首页</router-link>
    <img src="./assets/logo.jpg" style="width:200px;height:200px;">
  
    <router-link to="/news">新闻</router-link>

    <hr>

       <router-view></router-view>

  </div>
</template>

<script>



export default {     
      data () { 
        return {
         
         msg:'你好vue'
        }
      }
     
    }

</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
