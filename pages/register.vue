<template>
  <div class="register-page container">
    <div class="content">
      <div class="content__header">
        <h1>Buscacode</h1>
        <img src="~/assets/img/logo.svg" alt="">
      </div>
      <form method="POST">
        <div class="form-field">
          <input type="text" placeholder="Nombre" required>
        </div>
        <div class="form-field">
          <input type="text" placeholder="Apellidos" required>
        </div>
        <div class="form-field">
          <input type="email" placeholder="Email" required>
        </div>
        <div class="form-field">
          <input type="password" placeholder="Password" required>
        </div>
        <div class="form-submit">
          <button>Register</button>
        </div>
      </form>
      <p>
        ¿Tienes una cuenta? 
        <nuxt-link to="/login">Login</nuxt-link>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  layout: 'blank'
}
</script>
