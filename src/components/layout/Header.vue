<template>
  <div class="dizme_tm_header">
    <div class="container">
      <div class="inner">
        <div class="logo">
          <a href="#"
            ><img src="/img/logo/logo.png" alt=""
          /></a>
        </div>
        <div class="menu">
          <ul class="anchor_nav">
            <li class="current"><a href="#home">👋</a></li>
            <li><a href="#about">Sobre Mi</a></li>
            <!-- <li><a href="#portfolio">Portfolio</a></li> -->
            <li><a href="#service">Servicios</a></li>
            <!-- <li><a href="#blog">Blog</a></li> -->
            <li><a href="#contact">Contacto</a></li>
            <li class="download_cv">
              <a href="https://wa.me/584145014087" target="_blank"><span>Primera consulta GRATIS</span></a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderVue",
  props: {
    dark: { type: Boolean },
  },
};
</script>
