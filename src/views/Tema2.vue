<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Plataformas de distribución, festivales y medios de financiación

    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema2/img01.svg')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 A continuación, se podrán observar las plataformas de distribución, festivales de animación y cine, así como también varias maneras de gestionar medios de financiación para nuestros proyectos. Para ello hay ciertas pautas y requerimientos que dependiendo de las plataformas serán más o menos iguales, hay que tener en cuenta en cada uno los requisitos solicitados a la hora de aplicar para ellos. 
          br
          br
          br

    #t_2_1.titulo-segundo
    .h4 2.1 Proyectos para convocatorias y concursos
    p.mb-4 A raíz de la implementación de la Ley 1834 de 2017 con la que se fomenta la economía creativa y se regula la Ley Naranja, el país ha abierto espacios significativos para el desarrollo de las industrias culturales y creativas. A continuación, se verá una explicación al respecto:
      img(src="@/assets/curso/tema2/img03.svg")

    .row.justify-content-center.align-items-center.p-4.mb-4
      .col-lg-3.col-sm-4.mb-4
        button.buttom.color-primario.p-3.w-100.position-relative(data-bs-toggle='collapse' data-bs-target='.multi-collapse1' aria-expanded='true' aria-controls='.multi-collapse1')
          .row.justify-content-center.align-items-center
            .col-lg-12
              img.center.t(src='@/assets/curso/tema1/img16.svg')
              h5.mt-3 Creacion de convocatorias

      .col-lg-3.col-sm-4.mb-4
        button.buttom.color-primario.p-3.w-100.position-relative(data-bs-toggle='collapse' data-bs-target='.multi-collapse2' aria-expanded='true' aria-controls='.multi-collapse2')
          .row.justify-content-center.align-items-center
            .col-lg-4
              img.center.t(src='@/assets/curso/tema1/img17.svg')
              h5.mt-3 Requerimientos
      .col-lg-3.col-sm-4.mb-4
        button.buttom.color-primario.p-3.w-100.position-relative(data-bs-toggle='collapse' data-bs-target='.multi-collapse3' aria-expanded='true' aria-controls='.multi-collapse3')
          .row.justify-content-center.align-items-center
            .col-lg-4
              img.center.t(src='@/assets/curso/tema1/img18.svg')
              h5.mt-3 Restricciones      
      .col-lg-12.position-relative
        .multi-collapse1.collapse.show(data-bs-parent='#MapaGroup01')
            .col-lg-4
              .BG07.p-4.mb-4  
                h4.text-white.mb-0 Creación de convocatorias
              p Entre esos espacios se encuentra la creación de convocatorias para el desarrollo y fortalecimiento de proyectos artísticos y culturales, que se suman a las que ya venían de años anteriores como la Ley Filmación Colombia (2012) y el programa de Estímulos del Ministerio de Cultura.
        .multi-collapse2.collapse.show(data-bs-parent='#MapaGroup01')
          .row.mb-5            
            .col-4
            .col-4
              .BG04.p-4.mb-4  
                h4.text-white.mb-0 Requerimientos
              p Los requerimientos para presentarse en una convocatoria en Colombia son distintos, dependiendo de las condiciones que establezca la propia convocatoria, pero en general tienen que ver con tener un documento del proyecto o propuesta, ser ciudadano colombiano mayor de edad, no tener impedimentos para concursar con el Estado, no haber sido ganador en convocatorias anteriores y cumplir con los requisitos documentales que se soliciten.  
        .multi-collapse3.collapse.show(data-bs-parent='#MapaGroup01')
          .row.mb-5          
            .col-4
            .col-4
            .col-4
              .BG07.p-4.mb-4  
                h4.text-white.mb-0 Restricciones
              p Muchas convocatorias están restringidas a personas jurídicas o grupos constituidos, pero otras dan libre acceso también a personas naturales. 

      .cajon.color-acento-botones.p-4.mb-5
        p En el caso de los concursos, se debe contar con la pieza o contenido con el que se quiere participar tal y como lo establezca la dirección del evento y en la mayoría de los casos y contar con registro de propiedad intelectual.   
   
    .row.justify-content-center.mb-4
      .col-lg-4
        img(src="@/assets/curso/tema2/img04.png")
      .col-lg-8
        p.mb-4 Para Pedro Fuentes Rueda en Claves fundamentales para hacer un buen <i>pitching</i>
        p.mb-4 En el caso de los proyectos audiovisuales, en los últimos tiempos se ha impuesto el <i>PITCHING</i> como metodología para presentar los proyectos antes posibles financiadores. <i>PITCHING</i> quiere decir lanzar y, en proyectos audiovisuales se refiere a la venta de series, de largometrajes, de documentales, o de programas de televisión.         
        .BG04.p-2
          h4.text-white.mb-0 Publicado en la web: https://www.unir.net/humanidades/revista/claves-fundamentales-para-hacer-un-buen-pitching-audiovisual/

    .row.BG06.align-items-center.mb-4
      .col-lg-2
        img(src="@/assets/curso/tema2/img05.png")
      .col-lg-6
        i.fas.fa-quote-left
        p.mb-4 Los formatos de video son archivos de producción comprimidos y descomprimidos mediante un <i>códec</i>, todo lo cual se agrupa gracias a un contenedor. En estos se contienen metadatos, audios e información. Es decir, <i>códec</i> + contenedor = formato de video.
      .col-lg-4
        img(src="@/assets/curso/tema2/img06.png")
      .col-lg-8.mb-4
        .row.align-items-center.BG03.p-3
          .col-9
            p Para saber más sobre <i>Pitching</i> audiovisual, puede visitar el siguiente video: <i>TINET RUBIRA</i> (2020). <i>Pitching</i>: cómo vender nuestro proyecto | Creación Audiovisual. 
          .col-1
            .mb-3              
              a.boton.BG04.me-3(href="https://www.youtube.com/watch?v=fQPPpvuNzxk" target="_blank")
                span.text-white Ver          

      #t_2_2.titulo-segundo
        .h4 2.2 Convocatorias anuales para proyectos artísticos, culturales y festivales
      p.mb-4 A continuación, se podrá ver algunas convocatorias que generalmente se hacen anualmente en Colombia para proyectos artísticos, culturales y festivales:
      .row.justify-content-center.align-items-center.mb-4
        .col-lg-9   
          ImagenInfografica.color-primario.mb-5
            template(v-slot:imagen)
              figure 
                img(src='@/assets/curso/tema2/img07.svg', alt='Texto que describa la imagen')       
            .tarjeta.color-acento-botones.p-3(x="53%" y="06%" numero="1")
              p Programa Nacional de Estímulos
            .tarjeta.color-acento-botones.p-3(x="38%" y="15%" numero="2")
              p Programa departamental de Estímulos
            .tarjeta.color-acento-botones.p-3(x="52%" y="23%" numero="3")
              p Programa Distrital de Estímulos 2021
            .tarjeta.color-acento-botones.p-3(x="34%" y="30%" numero="4")
              p Convocatoria Jóvenes en Movimiento
            .tarjeta.color-acento-botones.p-3(x="44%" y="44%" numero="5")
              p Convocatoria Laboratorio Startup de APPS.CO 
            .tarjeta.color-acento-botones.p-3(x="63%" y="36%" numero="6")
              p Semilleros de Emprendimiento Digital de Apps.co
            .tarjeta.color-acento-botones.p-3(x="59%" y="57%" numero="7")
              p Fondo Emprender del SENA
            .tarjeta.color-acento-botones.p-3(x="62%" y="75%" numero="8")
              p Programa Nacional de Concertación Cultural
            .tarjeta.color-acento-botones.p-3(x="40%" y="61%" numero="9")
              p Festivales de emprendimiento: Héroes <i>Fest e InspiraTIC</i>

      .row.align-items-center.BG03.p-3
              .col-10
                p Para conocer en detalle las convocatorias y otras ayudas para la financiación de proyectos, puede visitar la siguiente página web: 
              .col-2
                .mb-3              
                  a.boton.BG04.me-3(href="https://economianaranja.gov.co/convocatorias/" target="_blank")
                    span.text-white Ver  

    #t_2_3.titulo-segundo
      .h4 2.3 Convocatorias para proyectos audiovisuales

    .row.mb-4
      .col.lg-5
        img(src="@/assets/curso/tema2/img09.png")
      
      .col-lg-7
        .row.mb-4
        ul.lista-ul
          li 
            i.fas.fa-caret-right
            | Convocatorias Audiovisuales MinTIC. 
        ul.lista-ul 
          li 
            i.fas.fa-caret-right
            | Crea digital.
        ul.lista-ul--separador
          li 
            i.fas.fa-caret-right
            | Ampliación beneficios Ley Filmación Colombia al sector audiovisual.
        ul.lista-ul--separador
          li 
            i.fas.fa-caret-right
            | Ley 814 de 2003: Estímulos e incentivos para las creación, producción, coproducción y realización de largometrajes y cortometrajes colombianos.
        ul.lista-ul--separador
          li 
            i.fas.fa-caret-right
            | Festival de Cine Verde de Barichara.
        ul.lista-ul--separador
          li 
            i.fas.fa-caret-right
            | Festival Internacional de Cine Independiente de Villa de Leyva.
        ul.lista-ul--separador
          li 
            i.fas.fa-caret-right
            | Festival Internacional de Cine de Cartagena.
        ul.lista-ul--separador
          li 
            i.fas.fa-caret-right
            | Festival de Cine Corto de Popayán.
        ul.lista-ul--separador
          li 
            i.fas.fa-caret-right
            | Festival de Cine de Bogotá.
        ul.lista-ul--separador
          li 
            i.fas.fa-caret-right
            | Festival Internacional de Cine de Cali.
        ul.lista-ul--separador
          li 
            i.fas.fa-caret-right
            | Festival Internacional de Cine de Santander.
        ul.lista-ul--separador
          li 
            i.fas.fa-caret-right
            | Festival Internacional de Cine de Barranquilla
        ul.lista-ul--separador
          li 
            i.fas.fa-caret-right
            | Festival de Cine e Infancia y Adolescencia.
      .row.align-items-center.BG03.p-3
        .col-11
          p Para conocer en detalle el total de festivales y muestras de cine colombiano que se realizan en el país, puede visitar el siguiente enlace: 
        .col-1
          a.boton.BG04.me-3(href="https://mincultura.gov.co/areas/cinematografia/Paginas/Festivales.aspx /" target="_blank")
            span.text-white.mb-2 Ver 
   
    .cajon.color-acento-botones.p-4
      p El proyecto de animación puede ser presentado en diversos eventos dedicados al mundo del entretenimiento digital, para ello debes tenerlo preparado; es decir, haber hecho todo el proceso de pipeline y demás, y así poder participar de dichos eventos.


</template>

<script>
export default {
  name: 'Tema2',
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
