<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="info">
      <b-navbar-brand href="#"></b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item href="/CreateUser">Crear usuarios</b-nav-item>
          <b-nav-item href="/ListUser">Ver usuarios</b-nav-item>
        </b-navbar-nav>

        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <img src="" alt="" />
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>
