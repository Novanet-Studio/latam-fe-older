<template>
  <section class="hero">
    <div class="hero__tv">
      <a class="hero__tv__box" href="#canales">
        <div class="hero__tv__icon"></div>
        <div class="hero__tv__info">
          <h1 class="hero__tv__title">TV por cable</h1>
          <p class="hero__tv__text">¡Son más de 100 canales!.<br />
             Tenemos nuevos canales para disfrutar en familia.
          </p>
        </div>
      </a>
    </div>
    <div class="hero__internet">
      <a class="hero__internet__box" href="/internet/">
        <div class="hero__internet__icon"></div>
        <div class="hero__internet__info">
          <h1 class="hero__internet__title">Internet por fibra</h1>
          <p class="hero__internet__text">
            Conexión en fibra óptica de alta velocidad para uso corporativo y residencial.
          </p>
        </div>
      </a>
    </div>
  </section>
</template>

<script>
export default {
  name: 'HeroSection',
}

import './Hero.scss'
</script>