<template>
   <div class="header">
     <div class="container">
       <div class="navbar">
         <div class="logo">
           <img src="./assets/logo-shopping.png" alt="logo" width="70">
         </div>

         <nav>
           <ul>
             <li><a href="#">Home</a></li>
             <li><a href="#">Products</a></li>
             <li><a href="#">About</a></li>
             <li><a href="#">Contact</a></li>
             <li><a href="#">Account</a></li>
           </ul>
         </nav>
       </div>
     </div>
   </div>

  <HelloWorld msg="Ecommerce Shit"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
/* body{
} */
.navbar{
  display: flex;
  align-items: center;
   padding: 20px;
}
nav{
  flex: 1;
  text-align: right;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
