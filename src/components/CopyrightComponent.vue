<template>
  <div class="dizme_tm_section">
    <div class="dizme_tm_copyright">
      <div class="container">
        <div class="inner">
          <div class="left wow fadeInLeft" data-wow-duration="1s">
            <p>
              Hecha con ❤️ 
              <a href="https://cala.la/" target="_blank"
                >cala.la</a
              >
              &copy; {{ new Date().getFullYear() }}
            </p>
          </div>
          <div class="right wow fadeInRight" data-wow-duration="1s">
            <ul>
              <!-- <li><a href="#">Terms &amp; Condition</a></li> -->
              <li><a href="#">Política de Privacidad</a></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "CopyrightComponent",
  components: {},
};
</script>
