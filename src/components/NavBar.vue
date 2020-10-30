<template>
  <header class="ftco-header">
    <nav class="navbar navbar-expand-lg navbar-dark ftco_navbar ftco-navbar-light" id="ftco-navbar">
      <div class="container">
        <a class="navbar-brand" href="/">IT-Together</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarContent"
          aria-controls="navbarContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="oi oi-menu"></span> Menu
        </button>

        <div class="collapse navbar-collapse" id="navbarContent">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item active"><a href="/" class="nav-link">Home</a></li>
            <li class="nav-item"><a href="services" class="nav-link">Szolgáltatások</a></li>
            <li class="nav-item"><a href="about" class="nav-link">Magunkról</a></li>
            <li class="nav-item"><a href="contact" class="nav-link">Elérhetőségek</a></li>
            <li class="nav-item"><a href="partners" class="nav-link">Együttműködő partnerünk</a></li>
          </ul>
        </div>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: "NavBar",
  props: {}
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.ftco-header {
    background: #315eff;
    position: relative;
    padding: 2em 0;
}

.ftco-header a {
    color: rgba(255, 255, 255, 0.7);
}

.navbar-brand {
    font-weight: 900;
}

.ftco-navbar-light .navbar-nav > .nav-item > .nav-link {
    font-size: 16px;
    padding-top: .9rem;
    padding-bottom: .9rem;
    padding-left: 20px;
    padding-right: 20px;
    color: rgba(255, 255, 255, 0.8);
    font-weight: 600;
    opacity: 1 !important;
}

.ftco-navbar-light {
    background: #315eff !important;
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    z-index: 3; 
}
</style>
