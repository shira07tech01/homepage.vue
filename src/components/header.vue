<template>
 <div id="header">
    <div class='fixed-top'>
      <b-navbar toggleable="lg" type="dark" variant="info">
        <b-navbar-brand href="#">
          <img src="../assets/MTM_logo.png" alt="Kitten" width="60" height="40">
        </b-navbar-brand>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav>
            <b-nav-item href="#">Link</b-nav-item>
            <b-nav-item href="#" disabled>Disabled</b-nav-item>
          </b-navbar-nav>

          <!-- Right aligned nav items-->
          <b-navbar-nav class="ml-auto">

          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>
 </div>
</template>

<script>
export default {
  name: 'header'
}
</script>

<style scoped>
  header{
    background-color: darkgreen;
    padding: 10px;
    height: 50px;
    text-align: center;
    color: #ffffFF;
  }
</style>
