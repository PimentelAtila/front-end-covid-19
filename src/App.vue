<template>
  <div id="app">
    <nav class="navbar navbar-expand navbar-light bg-light">
      <a href="#" class="navbar-brand">
        <img src="../src/assets/logo.png">
      </a>
      <div class="navbar-nav mr-auto">
        <li class="nav-item">
          <a href="/patients" class="nav-link">Pacientes</a>
        </li>
        <li class="nav-item">
          <a href="/adicionar" class="nav-link">Adicionar Paciente</a>
        </li>
      </div>      
    </nav>
    <div class="container-fluid mt-3">
      <router-view />
    
    </div>

  </div>
  
</template>

<script>

export default {
  name: 'App',
  components: {
  }
}

</script>

<style>
body{
  background-color:bisque;
}
.navbar{
  box-shadow: 0px 5px 5px 5px rgb(240, 11, 11);
  background-color:bisque;
}
.nav-item{
  border:1px solid #999;
  border-radius: 3px;
  margin-left: 5px;
}
.nav-item a{
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  font-size: 2.0rem;
  font-weight: 900;
  text-shadow: 2px 2px 8px #ccc;  
}
</style>
