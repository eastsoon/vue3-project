<template>
  <header>
    <nav class="navbar navbar-expand-sm navbar-dark bg-primary">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">JDS CODING</a>
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
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav me-auto">
            <li class="nav-item">
              <RouterLink to="/" active-class="active" class="nav-link"
                >Home</RouterLink
              >
            </li>
            <li class="nav-item">
              <RouterLink to="/about" active-class="active" class="nav-link"
                >About</RouterLink
              >
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>
</template>

<script setup></script>

<style lang="scss" scoped></style>
