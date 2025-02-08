<template>
  <div class="dizme_tm_section" id="about">
    <div class="dizme_tm_about">
      <div class="container">
        <div class="wrapper">
          <div class="left">
            <div class="image">
              <img :src="`/public/img/about/_1.jpg`" alt="" />
              <div class="numbers year">
                <div class="wrapper">
                  <h3>
                    <VueJsCounter end="7"></VueJsCounter>
                  </h3>
                  <span class="name">Años de<br />Experiencia</span>
                </div>
              </div>
              <div class="numbers project">
                <div class="wrapper">
                  <h3 style="display: flex">
                    +<VueJsCounter as="span" end="100"></VueJsCounter>
                  </h3>
                  <span class="name">Casos<br /> Clínicos</span>
                </div>
              </div>
            </div>
          </div>
          <div class="right">
            <div class="title wow fadeInUp" data-wow-duration="1s">
              <span>Mi frase favorita</span>
              <h3>"No se cura lo que no se enfrenta"</h3>
            </div>
            <div class="text wow fadeInUp" data-wow-duration="1s">
              <p>
                Combino técnicas cognitivo-conductuales con enfoques humanistas
                para abordar la raíz de tu malestar. En un espacio seguro y confidencial, 
                te acompaño a explorar patrones limitantes, cultivar la autocompasión 
                y desarrollar herramientas que promuevan cambios positivos 
                y duraderos en tu vida.
              </p>
            </div>
            <div class="dizme_tm_button wow fadeInUp" data-wow-duration="1s">
              <a class="anchor" href="#contact"><span>Cuéntame cómo puedo ayudarte</span></a>
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
