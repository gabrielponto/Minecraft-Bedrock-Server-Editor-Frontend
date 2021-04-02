<template>
  <div class="home">
    <img alt="Vue logo" class="logo" src="../assets/logo.png">
    <p>Aqui você pode gerenciar e ativar mundos, assim como addons</p>
    <div class="btn-group">
      <a class="btn btn-primary">Mundos</a>
      <a class="btn btn-secondary">Addons</a>
      <a class="btn btn-danger">Editar configurações</a>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Home',
}
</script>

<style scoped>
.logo {
  width:200px;
  margin-bottom:20px;
}
</style>
