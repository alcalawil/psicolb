<template>
  <div class="dizme_tm_section" id="quote">
    <div class="dizme_tm_quote">
      <div class="container">
        <div class="quote_wrapper wow fadeInUp" data-wow-duration="1s">
          <h3 class="quote_text">"No se cura lo que no se enfrenta"</h3>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "QuoteComponent",
  props: {
    dark: { type: Boolean },
  },
};
</script>

<style scoped>
.dizme_tm_quote {
  padding: 40px 0;
  position: relative;
}

.quote_wrapper {
  text-align: center;
  max-width: 800px;
  margin: 0 auto;
}

.quote_text {
  font-size: 2.5rem;
  font-weight: 300;
  line-height: 1.4;
  color: #333;
  font-style: italic;
  margin: 0;
  position: relative;
}

/* .quote_text::before {
  content: '"';
  font-size: 4rem;
  color: #ff6b6b;
  position: absolute;
  top: -20px;
  left: -30px;
  font-family: serif;
} */

/* .quote_text::after {
  content: '"';
  font-size: 4rem;
  color: #ff6b6b;
  position: absolute;
  bottom: -40px;
  right: -30px;
  font-family: serif;
} */

/* Dark mode styles */
.dizme_tm_all_wrap[data-theme="dark"] .quote_text {
  color: #fff;
}

@media (max-width: 768px) {
  .quote_text {
    font-size: 1.8rem;
  }
  
  .quote_text::before,
  .quote_text::after {
    font-size: 3rem;
  }
  
  .quote_text::before {
    left: -20px;
    top: -15px;
  }
  
  .quote_text::after {
    right: -20px;
    bottom: -30px;
  }
}
</style> 