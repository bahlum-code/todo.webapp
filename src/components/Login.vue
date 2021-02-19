<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-sm-6">
        <div id="Form__Login">
          <form>
            <div class="form-group">
              <label for="email">Correo electronico</label>
              <input type="email" class="form-control" id="email" aria-describedby="email">
            </div>
            <div class="form-group">
              <label for="password">Contraseña</label>
              <input type="password" class="form-control" id="password">
            </div>
            <div class="Form__Button">
              <button type="button" class="btn btn-primary">Ingresar</button>
            </div>
          </form>
        </div>
      </div>
      <div class="col-sm-6">
        IMAGEN
      </div>
    </div>
  </div>
</template>

<style>
  @import '../assets/css/styleLogin.css';
</style>
