<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Plataformas de distribución, festivales y medios de financiación
      
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema2/img01.svg')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-4 A continuación, se podrán observar las plataformas de distribución, festivales de animación y cine, así como también varias maneras de gestionar medios de financiación para nuestros proyectos. Para ello hay ciertas pautas y requerimientos que dependiendo de las plataformas serán más o menos iguales, hay que tener en cuenta en cada uno los requisitos solicitados a la hora de aplicar para ellos. 
    
    separador 
    #t_2_1.titulo-segundo.color-acento-contenido(data-aos="slide-right")
      h2 2.1 Proyectos para convocatorias y concursos

    p.mb-4 A raíz de la implementación de la Ley 1834 de 2017 con la que se fomenta la economía creativa y se regula la Ley Naranja, el país ha abierto espacios significativos para el desarrollo de las industrias culturales y creativas. A continuación, se verá una explicación al respecto:

    .gradient-bg_gris
      .row.justify-content-center
        .col-lg-10(data-aos="zoom-in")
          ImagenInfografica.color-secundario.mb-5
            template(v-slot:imagen)
              figure
                img(src='@/assets/curso/tema2/img03.svg')                

            .info_Card(x="15.9%" y="79.5%" numero="1")
              .info_Card--title
                h4.mb-0 Creación de convocatorias
              .info_Card--body
                p Entre esos espacios se encuentra la creación de convocatorias para el desarrollo y fortalecimiento de proyectos artísticos y culturales, que se suman a las que ya venían de años anteriores como la Ley Filmación Colombia (2012) y el programa de Estímulos del Ministerio de Cultura.

            .info_Card(x="48.8%" y="81%" numero="2")
              .info_Card--title
                h4.mb-0 Requerimientos
              .info_Card--body
                p Los requerimientos para presentarse en una convocatoria en Colombia son distintos, dependiendo de las condiciones que establezca la propia convocatoria, pero en general tienen que ver con tener un documento del proyecto o propuesta, ser ciudadano colombiano mayor de edad, no tener impedimentos para concursar con el Estado, no haber sido ganador en convocatorias anteriores y cumplir con los requisitos documentales que se soliciten.             

            .info_Card(x="83.2%" y="80.5%" numero="3")
              .info_Card--title
                h4.mb-0 Restricciones
              .info_Card--body
                p Muchas convocatorias están restringidas a personas jurídicas o grupos constituidos, pero otras dan libre acceso también a personas naturales. 
    .bg_C02.pb-4
      .cajon.color-acento-botones.p-4.mb-4
        p.mb-0 En el caso de los concursos, se debe contar con la pieza o contenido con el que se quiere participar tal y como lo establezca la dirección del evento y en la mayoría de los casos y contar con registro de propiedad intelectual.   
   
      .row.justify-content-center
        .col-lg-4.justify-content-center.mb-4(data-aos="flip-left")
          img(src="@/assets/curso/tema2/img04.png")
        .col-lg-8
          h3.mb-4 <strong> Para Pedro Fuentes Rueda en Claves fundamentales para hacer un buen <i>pitching</i></strong>
          p.mb-4 En el caso de los proyectos audiovisuales, en los últimos tiempos se ha impuesto el <i>PITCHING</i> como metodología para presentar los proyectos antes posibles financiadores. <i>PITCHING</i> quiere decir lanzar y, en proyectos audiovisuales se refiere a la venta de series, de largometrajes, de documentales, o de programas de televisión.         
          .BG04.p-2
            p.text-white.mb-0 Publicado en la #[i web]: https://www.unir.net/humanidades/revista/claves-fundamentales-para-hacer-un-buen-pitching-audiovisual/

    
    .bg_gray
      .row.justify-content-center.align-items-center.mb-4      
        .col-lg-8.order-2.order-lg-1
          .crd.crd--grd01
            .row.align-items-center
              .col-lg-3.d-none.d-lg-flex(data-aos="flip-right")            
                img(src="@/assets/curso/tema2/img05.png").img125           
              .col-lg-9.custom_quote.ps-5              
                p Un <i>pitching</i> puede darse en una reunión individual, pero el formato más habitual consiste en una presentación pública ante posibles inversores, productores y cadenas, en una presentación que dura alrededor de diez minutos y que se puede apoyar en un PowerPoint. Tras esto, llega un turno de preguntas por parte del público. 
          
          .row.align-items-center.mx-3.mg_neg--top
            .col-lg-12
              .BG03.p-3
                .row
                  .col
                    p.mb-0 Para saber más sobre <i>Pitching</i> audiovisual, puede visitar el siguiente video: #[strong TINET RUBIRA (2020)]. <i>Pitching</i>: cómo vender nuestro proyecto | Creación Audiovisual. 
                  .col-auto                
                    a.boton.btn--negro(href="https://www.youtube.com/watch?v=fQPPpvuNzxk" target="_blank").mb-0
                      span.text-white Ver
                        i.fa.fa-link.ms-2
        .col-lg-4.order-1.order-lg-2.mb-5.mb-lg-0(data-aos="flip-left")
          img(src="@/assets/curso/tema2/img06.svg").img350.m-auto
                     
    separador 

    #t_2_2.titulo-segundo.color-acento-contenido(data-aos="slide-right")
      h2 2.2 Convocatorias anuales para proyectos artísticos, culturales y festivales

    p.mb-4 A continuación, se podrá ver algunas convocatorias que generalmente se hacen anualmente en Colombia para proyectos artísticos, culturales y festivales:
    .gradient-bg_01 
      .row.justify-content-center.align-items-center.mb-4
        .col-lg-7(data-aos="zoom-in")
          ImagenInfografica.color-primario.mb-5
            template(v-slot:imagen)
              figure 
                img(src='@/assets/curso/tema2/img07.svg', alt='Texto que describa la imagen')       
            .tarjeta.color-acento-botones.p-3(x="50.8%" y="5.7%" numero="1")
              p.text-dark.mb-0 Programa Nacional de Estímulos
            .tarjeta.color-acento-botones.p-3(x="34.5%" y="15.2%" numero="2")
              p.text-dark.mb-0 Programa departamental de Estímulos
            .tarjeta.color-acento-botones.p-3(x="49.9%" y="23.2%" numero="3")
              p.text-dark.mb-0 Programa Distrital de Estímulos 2021
            .tarjeta.color-acento-botones.p-3(x="30.6%" y="30.3%" numero="4")
              p.text-dark.mb-0 Convocatoria Jóvenes en Movimiento
            .tarjeta.color-acento-botones.p-3(x="41%" y="43.5%" numero="5")
              p.text-dark.mb-0 Convocatoria Laboratorio #[i Startup] de APPS.CO 
            .tarjeta.color-acento-botones.p-3(x="60.8%" y="36.2%" numero="6")
              p.text-dark.mb-0 Semilleros de Emprendimiento Digital de Apps.co
            .tarjeta.color-acento-botones.p-3(x="57.1%" y="57.7%" numero="7")
              p.text-dark.mb-0 Fondo Emprender del SENA
            .tarjeta.color-acento-botones.p-3(x="59.7%" y="75.6%" numero="8")
              p.text-dark.mb-0 Programa Nacional de Concertación Cultural
            .tarjeta.color-acento-botones.p-3(x="36.9%" y="61.4%" numero="9")
              p.text-dark.mb-0 Festivales de emprendimiento: Héroe <i class = "text-dark">Fest e InspiraTIC</i>

      .row.align-items-center.BG03.p-3
        .col
          p.mb-0 Para conocer en detalle las convocatorias y otras ayudas para la financiación de proyectos, puede visitar la siguiente página #[i web]: 
        .col-auto            
          a.boton.BG04.me-3(href="https://economianaranja.gov.co/convocatorias/" target="_blank").mb-0
            span.mb-0.text-white Ver
              i.fa.fa-link.ms-2

    separador
    #t_2_3.titulo-segundo.color-acento-contenido(data-aos="slide-right")
      h2 2.3 Convocatorias para proyectos audiovisuales

    p A continuación, se podrá observar convocatorias para proyectos audiovisuales en Colombia:

    .row.mb-4
      .col-lg-5(data-aos="flip-left")
        img(src="@/assets/curso/tema2/img09.png").m-auto.img500
      .col-lg-7        
        ul.lista-ul--color.ms-4
          li
            <i class="fas fa-caret-right fa-lg"></i>
            | Convocatorias Audiovisuales MinTIC.          
          li 
            <i class="fas fa-caret-right fa-lg"></i>
            | Crea digital.       
          li 
            <i class="fas fa-caret-right fa-lg"></i>
            | Ampliación beneficios Ley Filmación Colombia al sector audiovisual.      
          li 
            <i class="fas fa-caret-right fa-lg"></i>
            | Ley 814 de 2003: Estímulos e incentivos para las creación, producción, coproducción y realización de largometrajes y cortometrajes colombianos.        
          li 
            <i class="fas fa-caret-right fa-lg"></i>
            | Festival de Cine Verde de Barichara.        
          li 
            <i class="fas fa-caret-right fa-lg"></i>
            | Festival Internacional de Cine Independiente de Villa de Leyva.      
          li 
            <i class="fas fa-caret-right fa-lg"></i>
            | Festival Internacional de Cine de Cartagena.        
          li 
            <i class="fas fa-caret-right fa-lg"></i>
            | Festival de Cine Corto de Popayán.        
          li 
            <i class="fas fa-caret-right fa-lg"></i>
            | Festival de Cine de Bogotá.        
          li 
            <i class="fas fa-caret-right fa-lg"></i>
            | Festival Internacional de Cine de Cali.        
          li 
            <i class="fas fa-caret-right fa-lg"></i>
            | Festival Internacional de Cine de Santander.        
          li 
            <i class="fas fa-caret-right fa-lg"></i>
            | Festival Internacional de Cine de Barranquilla.        
          li 
            <i class="fas fa-caret-right fa-lg"></i>
            | Festival de Cine e Infancia y Adolescencia.


    .row.align-items-center.BG03.p-3.mb-4
      .col
        p.mb-0 Para conocer en detalle el total de festivales y muestras de cine colombiano que se realizan en el país, puede visitar el siguiente enlace: 
      .col-auto
        a.boton.BG04.me-3(href="https://mincultura.gov.co/areas/cinematografia/Paginas/Festivales.aspx/" target="_blank").mb-0
          span.text-white.mb-2 Ver 
            i.fa.fa-link.ms-2
    
    .cajon.color-acento-botones.p-4
      p.mb-0 El proyecto de animación puede ser presentado en diversos eventos dedicados al mundo del entretenimiento digital, para ello debes tenerlo preparado; es decir, haber hecho todo el proceso de pipeline y demás, y así poder participar de dichos eventos.


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
