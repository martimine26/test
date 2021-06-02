<template>
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Nuxt SSR</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavDropdown">
      <ul class="navbar-nav">
        <li class="nav-item">
         <nuxt-link exact active-class="active" class="nav-link" aria-current="page" to="/">
         Home
         </nuxt-link>
        </li>
        <li class="nav-item">
         <nuxt-link active-class="active" class="nav-link" to="/about">
         About
         </nuxt-link>
        </li>
        <li class="nav-item">
         <nuxt-link class="nav-link" to="/users">
         Users
         </nuxt-link>
        </li>
          <li class="nav-item">
         <nuxt-link class="nav-link" to="/Login">
         Login
         </nuxt-link>
        </li>
      </ul>
    </div>
  </div>
</nav>
</template>