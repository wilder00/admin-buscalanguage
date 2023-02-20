<template>
  <div class="login-page container">
    <div class="content">
      <div class="content__header">
        <h1>Buscacode</h1>
        <img src="~/assets/img/logo.svg" alt="">
      </div>
      <form method="POST">
        <div class="form-field">
          <input type="email" placeholder="Email" required>
        </div>
        <div class="form-field">
          <input type="password" placeholder="Password" required>
        </div>
        <div class="form-submit">
          <button>Login</button>
        </div>
      </form>
      <p>
        ¿Sin una cuenta? 
        <nuxt-link to="/register">Register</nuxt-link>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  layout: 'blank'

}
</script>

