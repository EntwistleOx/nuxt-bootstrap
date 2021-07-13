<template>
  <div>
    <b-navbar toggleable="sm" type="light" variant="light">
      <b-navbar-toggle target="nav-text-collapse"></b-navbar-toggle>
      <b-navbar-brand>Nuxt con Bootstrap</b-navbar-brand>

      <b-collapse id="nav-text-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-text>Home</b-nav-text>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
    <b-container>
      <Characters />
    </b-container>
  </div>
</template>

<script>
export default {}
</script>
