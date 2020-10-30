<template>
  <NavBar/>
  <router-view/>
  <FootBar/>
</template>


<script>
import NavBar from "@/components/NavBar.vue";
import FootBar from "@/components/FootBar.vue";

export default {
  name: 'App',
  components: {
    NavBar, FootBar
  }
}
</script>


<style>
*, *::before, *::after {
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
}
body {
  min-height: 100vh;
  min-height: -webkit-fill-available;
}
html {
  height: -webkit-fill-available;
}

#app {
    margin: 0;
    background-color: #61ff3f2b;
    font-size: 16px;
    line-height: 1.6;
    font-weight: 500;
    min-height: 100vh;
}

.img {
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center center;
    width: 100%;
    border-radius: 4px;
    -webkit-box-shadow: 17px 25px 56px -22px rgba(0, 0, 0, 0.38);
    -moz-box-shadow: 17px 25px 56px -22px rgba(0, 0, 0, 0.38);
    box-shadow: 17px 25px 56px -22px rgba(0, 0, 0, 0.38);
}

.img-about {
    position: relative;
    z-index: 0;
    height: 700px;
}

.heading-section h2 {
    font-size: 40px;
    font-weight: 700;
}

h2 {
    line-height: 1.5;
    color: #203d67;
    font-weight: 400;
}

a:hover {
    text-decoration: none;
}

/* Small devices (portrait tablets and large phones, 600px and up) */
@media only screen and (min-width: 600px) {
    .flex-item {
        flex-basis: 100%;
    }

    .brand-text {
        display: none;
    }
}

/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {
    .flex-item {
        flex-basis: 45%
    }
    
    .brand-text {
        display: none;
    }
}

/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {
    .flex-item {
        flex-basis: 24%
    }

    .grid-container {
        display: grid;
        grid-template-columns: 25% 25% 25%;
        
    }

    .grid-item-copyright {
        grid-column: 1 / 4;
    }

    .brand-text {
        display: block;
    }
}
</style>