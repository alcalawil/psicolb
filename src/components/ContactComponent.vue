<template>
  <div class="dizme_tm_section" id="contact">
    <div class="dizme_tm_contact">
      <div class="container">
        <div class="dizme_tm_main_title" data-align="center">
          <span>Contacto</span>
          <h3>¿Cómo puedo ayudarte?</h3>
          <!-- <p>
            Please fill out the form on this section to contact with me. Or call
            between 9:00 a.m. and 8:00 p.m. ET, Monday through Friday
          </p> -->
        </div>
        <div class="contact_inner">
          <div class="left wow fadeInLeft" data-wow-duration="1s">
            <ul>

              <li>
                <div class="list_inner">
                  <div class="icon purpleBackground">
                    <i class="icon-phone purpleText"></i>
                  </div>
                  <div class="short">
                    <a href="https://wa.me/584145014087" target="_blank"
                      ><span><h3>Whatsapp</h3></span></a>
                  </div>
                </div>
              </li>


              <li>
                <div class="list_inner">
                  <div class="icon greenBackground">
                    <i class="icon-calendar-1 greenText"></i>
                  </div>
                  <div class="short">
                    <a href="" onclick="Calendly.initPopupWidget({resize: true, url: 'https://calendly.com/cegarraliliana1/30min?hide_gdpr_banner=1&primary_color=FFA500&locale=es'});return false;">
                    <h3>Agenda tu Consulta</h3>
                  </a>
                  </div>
                </div>
              </li>

              <li>
                <div class="list_inner">
                  <div class="icon orangeBackground">
                    <i class="icon-location orangeText"></i>
                  </div>
                  <div class="short">
                    <h3>Terapia Presencial</h3>
                    <span>Barquisimeto Zona Este, Venezuela</span>
                  </div>
                </div>
              </li>

            </ul>
          </div>
          <div class="right wow fadeInRight" data-wow-duration="1s">
            <div class="fields">
              <form
                action="/"
                method="post"
                class="contact_form"
                id="contact_form"
                autocomplete="off"
              >
                <div
                  class="returnmessage"
                  data-success="Your message has been received, We will contact you soon."
                ></div>
                <div class="empty_notice">
                  <span>Please Fill Required Fields</span>
                </div>
                <div class="input_list">
                  <ul>
                    <li>
                      <input id="name" type="text" placeholder="Nombre" />
                    </li>
                    <li>
                      <input id="email" type="text" placeholder="Correo" />
                    </li>
                    <li>
                      <input
                        id="phone"
                        type="number"
                        placeholder="Teléfono"
                      />
                    </li>
                    <li>
                      <input id="subject" type="text" placeholder="Subject" />
                    </li>
                  </ul>
                </div>
                <div class="message_area">
                  <textarea
                    id="message"
                    placeholder="Descríbeme tu situación, o lo que quieras que sepa de ti"
                  ></textarea>
                </div>
                <div class="dizme_tm_button">
                  <a id="send_message" href="#"><span>Enviar</span></a>
                </div>
              </form>
            </div>
          </div>
          <div class="brush_2 wow fadeInRight" data-wow-duration="1s">
            <img src="/public/img/brushes/contact/2.png" alt="" />
          </div>
        </div>
        <div class="dizme_tm_map wow fadeInUp" data-wow-duration="1s">
          <div class="mapouter">
            <div class="gmap_canvas">
              <iframe
                width="100%"
                height="375"
                id="gmap_canvas"
                src="https://maps.google.com/maps?width=100%25&amp;height=600&amp;hl=en&amp;q=Barquisimeto+(Barquisimeto%20Este)&amp;t=&amp;z=14&amp;ie=UTF8&amp;iwloc=B&amp;output=embed"
                frameborder="0"
                scrolling="no"
                marginheight="0"
                marginwidth="0"
              ></iframe
              ><a
                href="https://www.embedgooglemap.net/blog/divi-discount-code-elegant-themes-coupon"
              ></a>
            </div>
          </div>

          <!-- Get your API here https://www.embedgooglemap.net -->
        </div>
      </div>
      <div class="brush_1 wow fadeInLeft" data-wow-duration="1s">
        <img src="/public/img/brushes/contact/1.png" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ContactComponent",
  components: {},
};
</script>
