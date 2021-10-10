<template>
  <div class="header">
    <div class="headerWrapper">
      <img src="../assets/sakiyama_ロゴ2.png" alt="" class="logo">
      <div id="nav">
        <router-link to="/">Home</router-link> 
        <router-link to="/about">About</router-link> 
        <router-link to="/Profile">Profile</router-link> 
        <router-link to="/Contact">Contact</router-link>
        <a href="https://facebook.com" target="_blank" rel="noopener noreferrer">F</a>
      </div>
    </div> 
  </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

* {
  font-family: 'Titillium Web', sans-serif;
}

a {
  color: #42b983;
}

.header {
  background-color: transparent;
  /* box-shadow: 0 2px 10px rgba(0,0,0,0.1); */
  width: 100%;
  position: absolute;
  z-index: 2;
}

.headerWrapper {
  display: flex;
  justify-content: space-between;
  padding: 20px 30px;
}

.headerWrapper .logo {
  cursor: pointer;
  height: 30px;
}

.headerWrapper #nav a {
  font-weight: bold;
  color: #2c3e50;
  text-decoration: none;
  margin: 0 40px;
  line-height: 30px;
}

.headerWrapper #nav a:hover {
  border-bottom: 1px solid #2c3e50;
}

.headerWrapper #nav a.router-link-exact-active {
  color: #d6c050;
  text-decoration: #d6c050;
  transition: .3s;
}

.headerWrapper #nav a.router-link-exact-active:hover {
  border-bottom: 1px solid #d6c050;
}


</style>
