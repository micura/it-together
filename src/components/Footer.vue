<template>
  <footer class="ftco-footer text-white">
    <div class="grid-container">
      <div class="grid-item">
        <ul class="list-unstyled">
          <li><a href="services/1.html" class="py-2 d-block">Weboldal készítés</a></li>
          <li><a href="services/2.html" class="py-2 d-block">Vállalatirányítási megoldások – ChaRM</a></li>
          <li><a href="services/3.html" class="py-2 d-block">Provisoning és számlázó rendszer – Maverix</a></li>
          <li><a href="services/4.html" class="py-2 d-block">Alközponti megoldások – Asterisk</a></li>
          <li><a href="services/5.html" class="py-2 d-block">Call, contact center megoldás</a></li>
          <li><a href="services/6.html" class="py-2 d-block">IT Support</a></li>
        </ul>
      </div>

      <div class="grid-item">
        <ul class="list-unstyled">
          <li><a href="services/7.html" class="py-2 d-block">Kamerarendszer kiépítések</a></li>
          <li><a href="services/8.html" class="py-2 d-block">Hangrögzítő megoldások</a></li>
          <li><a href="services/9.html" class="py-2 d-block">Hálózati megoldások </a></li>
          <li><a href="services/10.html" class="py-2 d-block">Backup-rendszer kialakítása</a></li>
          <li><a href="services/11.html" class="py-2 d-block">Pályázati támogatás</a></li>
        </ul>
      </div>
      <div class="grid-item">
        <ul class="list-unstyled">
          <li class="py-2 d-block">
            <span class="mr-3 fas fa-map-marker"></span>
            <span>1047 Budapest, Fóti út 56.</span>
          </li>
          <li class="py-2 d-block"><a href="#">
              <span class="mr-3 fas fa-user"></span>
              <span>+36 (70) 452-6883</span></a>
          </li>
          <li class="py-2 d-block"><a href="#">
              <span class="mr-3 fas fa-envelope"></span>
              <span>info@it-together.hu</span></a>
          </li>
        </ul>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.ftco-footer {
    background: #315eff;
    position: relative;
    padding: 2em 0;
}

.ftco-footer a {
    color: rgba(255, 255, 255, 0.7);
}

.grid-container {
    display: grid;
    justify-content: center;
}

.grid-item-copyright {
    text-align: center;
}
</style>
