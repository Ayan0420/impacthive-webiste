<template>
<nav class="navbar navbar-expand-lg bg-light shadow-sm sticky-top">
  <div class="container">
    <a class="navbar-brand" href="#">
        <img class="img-fluid" width="120" src="@/assets/images/impactHive-logo.png" alt="">
    </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item">
          <router-link class="nav-link active" aria-current="page" to="/">Home</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="/services">Services</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="/about">About</router-link>
        </li>
        <span class="vr mx-3" ></span>
        <li>
          <a class="ms-2 btn btn-primary rounded-pill px-4" href="#">Book Now!</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
</template>