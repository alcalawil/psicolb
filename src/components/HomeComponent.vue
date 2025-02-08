<template>
  <div class="dizme_tm_section" id="home">
    <div class="dizme_tm_hero">
      <div
        class="background"
        data-img-url="/public/img/slider/1.jpg"
      ></div>
      <div class="container">
        <div class="content">
          <div class="details">
            <div class="hello">
              <h3 class="orangeText">Hola, soy</h3>
            </div>
            <div class="name">
              <h3>Liliana Briceño<option value=""></option></h3>
            </div>
            <div class="job">
              <p>
                Licenciada en<span class="greenText"> Psicología</span>
                <!-- <span class="purpleText">Humanista</span> -->
              </p>
            </div>
            <div class="text">
              <p>
                Enfoque en terapia cognitivo conductual, apasionada y plenamente comprometida con el bienestar humano.
              </p>
            </div>
            <div class="button">
              <div class="dizme_tm_button">
                <a class="anchor" href="#about"><span>Sobre Mi</span></a>
              </div>
              <div class="social">
                <ul>
                  <li>
                    <a href="https://www.instagram.com/psicologiamundialb/" target="_blank" rel="noopener noreferrer">
                     <i class="icon-instagram-3"></i>
                    </a>
                  </li>
                  <li>
                    <a href="https://www.tiktok.com/@psicologiamundialb" target="_blank" rel="noopener noreferrer"><i class="icon-twitter-1"></i></a>
                  </li>
                  <li>
                    <a href="https://www.linkedin.com/in/liliana-briceño-cegarra-570878306/"><i class="icon-linkedin-1"></i></a>
                  </li>
                </ul>
              </div>
            </div>
          </div>
          <div class="avatar">
            <div class="image">
              <img src="/public/img/slider/avatar.png" alt="" />
              <span
                class="skills illustrator anim_moveBottom"
              ><img src="/public/img/svg/skills/brain.svg" /></span>
              <span class="skills photoshop anim_moveBottom"><img src="/public/img/svg/skills/brain_gym.svg" /></span>
              <span class="skills figma anim_moveBottom" ><img src="/public/img/svg/skills/brain_idea.svg" /></span>
            </div>
          </div>
        </div>
      </div>
      <div class="dizme_tm_down">
        <a class="anchor" href="#process" v-html="dark ? mouseDark : mouse">
        </a>
      </div>
    </div>
  </div>
</template>

<script>
import { ai, figma, mouse, mouseDark, ps } from "../svg";
export default {
  name: "HomeComponent",
  data() {
    return { ai, ps, figma, mouse, mouseDark };
  },
  props: {
    dark: { type: Boolean },
  },
};
</script>
