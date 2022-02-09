<template>
  <nav class="navbar navbar-expand-lg navbar-dark static-top mb-5" style="background-color: #007dc6;">
    <div class="container">
      <a class="navbar-brand bg-white" href="#">
        <img src="./../assets/logo.png" alt="..." height="36">
      </a>
      <button class="navbar-toggler ml-auto" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <!-- ml-auto still works just fine-->
        <ul class="navbar-nav ml-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Features</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Pricing</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
              Dropdown link
            </a>
            <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
              <a class="dropdown-item" href="#">Action</a>
              <a class="dropdown-item" href="#">Another action</a>
              <a class="dropdown-item" href="#">Something else here</a>
            </div>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>

export default {
  name: 'menu-bar',
  data() {
    return {
      
    }
  }
}
</script>
<style scoped>
.company-logo {
  width: 100%;
}
.navbar-brand {                
    position: absolute;
    left: 10%;
    top: 0px;
    width: 150px;        
    margin-left: 0px;
    padding: 30px;
    border: 5px solid #74bc1f;
}
</style>