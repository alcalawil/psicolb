<template>
  <div class="dizme_tm_header">
    <div class="container">
      <div class="inner">
        <div class="logo">
          <a href="#">
            <img src="/img/logo/logo.png" alt="" />
          </a>
        </div>
        <div class="menu">
          <ul class="anchor_nav">
            <li class="current"><a href="#home">👋</a></li>
            <li><a href="#about">Sobre Mi</a></li>
            <li><a href="#service">Servicios</a></li>
            <li><a href="#contact">Contacto</a></li>
            <li class="download_cv">
              <!-- En lugar de enlazar a WhatsApp, usamos @click para abrir Calendly -->
              <a href="" onclick="Calendly.initPopupWidget({resize: true, url: 'https://calendly.com/cegarraliliana1/30min?hide_gdpr_banner=1&primary_color=f65123&locale=es'});return false;">
                <span>Agendar Cita</span>
              </a>
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
