<template>
<section class="jumbotron text-center">
    <div class="container">
      <h1>Welcome</h1>
      <p class="lead text-muted">
          Generate and share links to earn 10% of the product price
      </p>
      <p>
        <router-link to="/login" class="btn btn-primary my-2">Login</router-link>
        <router-link to="/register" class="btn btn-secondary my-2">Register</router-link>
      </p>
    </div>
  </section>
</template>

<script>
export default {
    name: "Header",
    setup () {
        return {}
    }
}
</script>