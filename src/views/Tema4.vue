<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Demo Reel

    .row.mb-4
      .col.lg-5
        img(src="@/assets/curso/tema4/img01.png")
      .col-lg-7
        p.mb-4 Es una técnica personalizada que consiste en realizar un video corto, en el que se hace la presentación de un currículo, portafolio gráfico o una recopilación de los mejores trabajos o proyectos que ha realizado un artista o cualquier otro individuo relacionado con alguna expresión artística audiovisual como diseñadores, cantantes, animadores, editores, modelos, fotógrafos, entre otros; con el objetivo de resaltar sus destrezas y habilidades, para promover su talento y potencial.
        .cajon.color-acento-botones.p-4
          p Por lo tanto, un demo reel se puede considerar como una carta de presentación donde se exhibe las habilidades y talento de un individuo, haciendo que se destaque y se diferencie de entre la multitud; por lo cual es necesario conocer los principales aspectos que se deben tener en cuenta a la hora de su creación.
        <br>
        <br>
        p.mb-4 Siendo así, a continuación, se relacionan unos aspectos importantes a tener en cuenta al momento de la creación de un demo reel:

                
</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
