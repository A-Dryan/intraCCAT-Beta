<template>
  <div id="nav">
     <div class="titulo-router">C C A T</div>
    <router-link to="/">MOD. HOME</router-link><hr>
    <router-link to="/about">MOD. PROYECTO</router-link><hr>
    <router-link to="/nosotros">MOD. NOSOTROS</router-link><hr>
    <router-link to="/miembros">MOD. MIEMBROS</router-link><hr>
    <router-link to="/direcciongerencia">MOD. DIRECCION/GERENCIA</router-link><hr>
    <router-link to="/proxeventos">MOD. PROX EVENTOS</router-link><hr>
  </div>
  <router-view/>
</template>

<style>

hr {
  height: 1px;
  background-color: #e4e4e4;
  border-top: none;
}

#app {
  display: flex;
    font-family: 'Open Sans', sans-serif;
    background: #e4e4e4;
    height: 100vh;
}

#nav {
  display: flex;
  flex-direction: column;
  align-content: center;
  width: 17%;
  font-size: 2vh;
  background: #fff;
}

.titulo-router{
  display: block;
   padding: 2vh 2vw;
  text-align: center;
  background: rgb(86, 160, 221);
  color: #fff;
}
#nav a {
    padding: 1.5vh 2vw;
    text-decoration: none;  
    color: rgb(95, 95, 95);
    outline: none;
}

#nav a:hover{
  background: #e4e4e4;
}
#nav hr{
  color: #e4e4e4;
  margin: 0;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
