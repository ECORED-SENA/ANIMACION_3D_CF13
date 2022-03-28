<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-3.p-md-5.mb-4
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span i
      h1 Introducción

    .gradient-bg_01   
      .row.justify-content-center 
        .col-lg-6         
          .bloque-texto-d.color-secundario.p-4
            .bloque-texto-d__texto.mb-2
              p.mb-0 Estimado aprendiz, en el siguiente video se cuenta con una visión general del componente formativo que da cierre a este interesante curso #[strong Animación 3D:]        
        .col-lg-6      
          figure
            img(src="@/assets/curso/intro/intro.svg", alt="alt", style="width:450px;").m-auto

      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/BSctkDEniJs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen) 

           
      
    
   
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
