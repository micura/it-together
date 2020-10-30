<template>
  <div class="container">
    <div class="row mt-4">
      <div class="col">
        <div class="heading-section mb-2 mt-0">
          <h2 class="mb-3">Elérhetőség</h2>
        </div>
      </div>
    </div>
    
    <div class="row">
      <div class="col-md-3">
        <p><span>Cím:</span> 1047 Budapest, Fóti út 56.</p>
      </div>
      <div class="col-md-3">
        <p><span>Telefon:</span> <a href="tel://06704526883">+36 (70) 452-6883</a></p>
      </div>
      <div class="col-md-3">
        <p><span>Email:</span> <a href="mailto:info@it-together.hu">info@it-together.hu</a></p>
      </div>
      <div class="col-md-3">
        <p><span>Weboldal:</span> <a href="https://it-together.hu">https://it-together.hu</a></p>
      </div>
    </div>

    <div class="row block-9">
      <div class="col-md-6 pr-md-5">
        <form action="#">
          <div class="form-group">
            <input type="text" class="form-control" placeholder="Név">
          </div>
          <div class="form-group">
            <input type="text" class="form-control" placeholder="Email">
          </div>
          <div class="form-group">
            <input type="text" class="form-control" placeholder="Tárgy">
          </div>
          <div class="form-group">
            <textarea name="" id="" cols="30" rows="7" class="form-control" placeholder="Üzenet"></textarea>
          </div>
          <div class="form-group">
            <input type="submit" value="Üzenet küldése" class="btn btn-primary py-3 px-5">
          </div>
        </form>

      </div>

      <div class="col-md-6">
        <div class="mapouter">
          <div class="gmap_canvas"><iframe width="600" height="500" id="gmap_canvas"
              src="https://maps.google.com/maps?q=1047%20Budapest%2C%20F%C3%B3ti%20%C3%BAt%2056.&t=&z=13&ie=UTF8&iwloc=&output=embed"
              frameborder="0" scrolling="no" marginheight="0" marginwidth="0"></iframe><a
              href="https://www.whatismyip-address.com/nordvpn-coupon/"></a></div>
        </div>
      </div>
    </div>

  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Contact",
  components: {
  }
};
</script>

<style scoped>
  .mapouter {
    position: relative;
    text-align: right;
    height: 500px;
    width: 600px;
  }

  .gmap_canvas {
    overflow: hidden;
    background: none !important;
    height: 400px;
    width: 600px;
  }
</style>