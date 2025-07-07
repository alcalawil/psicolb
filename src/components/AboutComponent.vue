<template>
  
  <div class="dizme_tm_section" id="about">
    <div class="dizme_tm_about">
      <div class="container">
        <div class="wrapper">
          <div class="left">
            <div class="image">
              <img src="/public/img/about/1.jpg" alt="" />

              <!-- <div class="numbers year">
                <div class="wrapper">
                  <h3>
                    <VueJsCounter end="+7"></VueJsCounter>
                  </h3>
                  <span class="name">Años de<br />Experiencia</span>
                </div>
              </div> -->
              <div class="numbers project">
                <div class="wrapper">
                  <h3 style="display: flex">
                    +<VueJsCounter as="span" end="5"></VueJsCounter>
                  </h3>
                  <span class="name">Años de<br /> Experiencia</span>
                </div>
              </div>
            </div>
          </div>
          <div class="right">
            <div class="title wow fadeInUp" data-wow-duration="1s">
              <span>Sobre Mi</span>
              <!-- <h3>"No se cura lo que no se enfrenta"</h3> -->
            </div>
            <div class="text wow fadeInUp" data-wow-duration="1s">
              <p>
                Más  allá de lo profesional, soy alguien que ama amar, que encuentra en la música y el baile una forma de expresarse y conectarse con la vida, creo profundamente en el poder del autoconocimiento como motor de cambio.
Amo mi profesión porque me permite estar presente en momentos significativos de la vida de las personas, ser testigo de sus luchas, sus logros y en la magia que ocurre cuando alguien se anima a mirar hacia adentro. Si estás en ese camino, acá estoy.

              </p>
              <!-- <p>
                Te ofrezco un espacio seguro y de confianza, 
                en donde puedas desarrollar herramientas que te ayuden a gestionar emociones  
                y afrontar los retos de la vida cotidiana.
              </p> -->
            </div>
            <div class="dizme_tm_button wow fadeInUp" data-wow-duration="1s">
              <a class="anchor" href="#contact"><span>¿Cómo puedo ayudarte?</span></a>
            </div>
          </div>
        </div>
      </div>
      <div class="brush_1 wow fadeInLeft" data-wow-duration="1s">
        <img src="/public/img/brushes/about/1.png" alt="" />
      </div>
      <div class="brush_2 wow fadeInRight" data-wow-duration="1s">
        <img src="/public/img/brushes/about/2.png" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
import VueJsCounter from "vue-js-counter";
export default {
  name: "AboutComponent",
  components: { VueJsCounter },
  props: {
    dark: { type: Boolean },
  },
};
</script>
