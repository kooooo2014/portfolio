<template>
  <div class="header">
    <div class="headerWrapper">
      <img src="../assets/sakiyama_ロゴ2.png" alt="" class="logo">
      <div id="nav">
        <a href="#" target="_blank" rel="noopener noreferrer">Home</a>
        <a href="#about" target="_blank" rel="noopener noreferrer">About</a>
        <a href="#skill" target="_blank" rel="noopener noreferrer">Skill</a>
        <a href="#works" target="_blank" rel="noopener noreferrer">Works</a>
        <a href="#carrer" target="_blank" rel="noopener noreferrer">Carrer</a>
        <a href="#contact" target="_blank" rel="noopener noreferrer">Contact</a>
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
  border-bottom: 1px solid #d6c050;
  color: #d6c050;
  text-decoration: #d6c050;
  transition: .3s;
}

</style>
