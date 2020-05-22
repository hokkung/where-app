<template>
  <div class="nav-bar">
    <b-navbar toggleable="lg" variant="faded" type="light">
      <b-navbar-brand class="mb-0">
        <div class="logo">
          <h1>WHERE?</h1>
        </div>
      </b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item href="#">ABOUT US</b-nav-item>
          <b-nav-item href="#">OUR SERVICE</b-nav-item>
        </b-navbar-nav>
        <b-navbar-nav class="ml-auto">
          <b-nav-item href="#">
            <font-awesome-icon :icon="['fab', 'facebook-f']" />
          </b-nav-item>
          <b-nav-item href="#">
            <font-awesome-icon icon="mobile-alt"
          /></b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: "NavBar",
  props: {}
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.nav-bar {
  font-family: "Source Sans Pro", sans-serif;
}
.nav-bar .logo {
  font-size: 50px;
}

.nav-item {
  font-size: 23px;
  margin-left: 20px;
  margin-right: 20px;
}
</style>
