<template>
  <nav class="navbar navbar-expand-lg">
    <div class="container-fluid">
      <a style="text-shadow: 1px 1px 2px pink;" class="navbar-brand text-white" href="#"><strong>LEE LEE</strong></a>
      <button class="navbar-toggler bg-white" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <div class="navbar-nav me-auto mb-2 mb-lg-0">
        </div>
        <div class="d-flex bg-white border rounded">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active mx-3 custom-primary-color" href="#">
                <i class="fa-solid fa-house"> </i>
                <strong> HOME</strong>
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link mx-3 custom-primary-color" href="#">
              <strong>APP</strong>
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link mx-3 custom-primary-color" href="#">
               <strong>ABOUT</strong>
              </a>
            </li>
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle custom-primary-color" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                <i class="fa-solid fa-globe ps-3"></i>
              </a>
              <ul class="dropdown-menu custom-primary-color">
                <li><a class="dropdown-item" href="#">EN</a></li>
                <li><a class="dropdown-item" href="#">ES</a></li>
              </ul>
            </li>
            <li class="nav-item">
              <a class="nav-link mx-3 custom-primary-color" href="#">
                <i class="fa-solid fa-right-to-bracket"></i>
                <strong> LOGIN</strong>
              </a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </nav>
<!--  <nav class="navbar navbar-expand-md bg-faded justify-content-center">
    <a href="#" class="navbar-brand p-3 text-white d-flex w-50 mr-auto"><strong>LEE LEE</strong></a>
    <button class="navbar-toggler bg-white" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="navbar-collapse collapse w-100" id="navbarSupportedContent">
&lt;!&ndash;      <ul class="navbar-nav bg-white p-2 w-100 justify-content-center">
        <li class="nav-item">
          <a class="nav-link active mx-3" aria-current="page" href="#">
            <i class="fa-solid fa-house"></i>
            <strong> HOME</strong>
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link mx-3" href="#">
            <strong>APP</strong>
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link mx-3" href="#">
            <strong>ABOUT</strong>
          </a>
        </li>
      </ul>&ndash;&gt;
      <ul class="nav navbar-nav bg-white p-2 ml-auto w-100 justify-content-end">
        <li class="nav-item">
          <a class="nav-link active mx-3" aria-current="page" href="#">
            <i class="fa-solid fa-house"></i>
            <strong> HOME</strong>
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link mx-3" href="#">
            <strong>APP</strong>
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link mx-3" href="#">
            <strong>ABOUT</strong>
          </a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            <i class="fas fa-globe"></i>
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">EN</a></li>
            <li><a class="dropdown-item" href="#">ES</a></li>
          </ul>
        </li>
        <li class="nav-item">
          <a class="nav-link mx-3" href="#">
            <i class="fa-solid fa-right-to-bracket"></i>
            <strong> LOGIN</strong>
          </a>
        </li>
      </ul>
    </div>
  </nav>-->
</template>

<script>
export default {
  name: "NavbarComponent",
  components: {}
}
</script>

<style scoped>
  nav {
    z-index: 1500;
    position: absolute;
    color: bisque !important;
    width: 100%;
  }
  .custom-primary-color {
    color: #e0602d;
  }

</style>
