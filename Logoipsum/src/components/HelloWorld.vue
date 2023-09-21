<script setup>

</script>

<template>
  <header class="header">
    <div class="container">
        <nav class="nav">
            <a href="#!" class="logo">
                <img src="./img/icons/logo.svg" alt="Logo">
            </a>

            <ul class="nav__list">
                <li><a href="#!" class="active">Home</a></li>
                <li><a href="#!">About</a></li>
                <li><a href="#!">Packages</a></li>
                <li><a href="#!">FAQ</a></li>
                <li><a href="#!">Community</a></li>
            </ul>

            <div class="nav__btns">
                <a href="#!" class="btn-login">Login</a>
                <a href="#!" class="btn-signup">Signup</a>
            </div>
        </nav>
    </div>
</header>
</template>

<style scoped>.nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 32px;
}

.nav__list {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 24px;

  a {
      color: #181818;
  }

  a:hover, a.active {
      color: #35AFF4;
  }
}

.nav__btns {
  display: flex;
  gap: 12px;
}

</style>
