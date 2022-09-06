<template>
  <nav
    class="navbar navbar-expand-lg navbar-dark bg-dark nav justify-content-end"
  >
    <div class="container-fluid ">
      <a class="navbar-brand" href="#">
        <img src="../components/img/stocco.svg" />
      </a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="justify-content-end collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav justify-content-end">
          <li class="nav-item">
            <a class="nav-link" href="#">TRABALHE CONOSCO</a>
          </li>
          <li class="nav-item light">
            <a class="nav-link" href="#">NOSSA MISSÃO</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">VALORES</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
    
export default {
  name: "Navbar",
};
</script>

<style>

</style>
