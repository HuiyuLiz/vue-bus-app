<template>
  <!-- navbar -->
  <nav class="navbar navbar-expand-lg navbar-light border-bottom py-3">
    <div class="container">
      <a
        class="navbar-brand"
        href="/"
      >
        <img
          src="../assets/image/logo.svg"
          alt="logo"
          class="img-fluid"
        >

      </a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon" />
      </button>
      <div
        id="navbarSupportedContent"
        class="collapse navbar-collapse justify-content-center align-center"
      >
        <div>
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item mx-4">
              附近站牌
            </li>
            <li class="nav-item mx-4">
              路線規劃
            </li>
            <li class="nav-item mx-4">
              站點查詢
            </li>
            <li class="nav-item mx-4">
              收藏站牌
            </li>
          </ul>
        </div>
      </div>
      <div class="d-none d-lg-flex align-items-center">
        <div class="me-2">
          <img
            src="../assets/image/iconoir_language.svg"
            alt="language"
          >
        </div>
        <div>中文 ｜ 英文</div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style lang="scss" scoped>
.navbar-brand {
  img {
    width: 10rem;
  }
}
</style>
