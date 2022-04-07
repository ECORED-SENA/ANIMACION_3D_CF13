<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Formatos y exportación

    .gradient-bg_green
      .row.align-items-center.mb-5
        .col-lg-7       
          p.mb-4 Los formatos de video son archivos de producción comprimidos y descomprimidos mediante un <i>códec</i>, todo lo cual se agrupa gracias a un contenedor. En estos se contienen metadatos, audios e información. Es decir, <i>códec</i> + contenedor = formato de video.
        .col-lg-5(data-aos="flip-right")
          img(src="@/assets/curso/tema1/img01.png").img500


    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="slide-right")
      h2 1.1 Relación de aspecto (<i>Aspect ratio</i>)    
     
    
    .row.mb-5
      .col-lg-5(data-aos="flip-left")
        img(src="@/assets/curso/tema1/img_02.png", style="width:450px;").m-auto
      .col-lg-7
        <br><br>
        p.mb-4 Es la relación entre el ancho y el alto de la imagen, donde X es el ancho y Y es el alto, por ejemplo 1:1 significa que tiene proporciones iguales, como 500 x 500 px (pixeles) o 1920 x 1920 px. Un video con una relación de 1920 x 1080 px tiene una relación de aspecto de 16:9, esto quiere decir que el alto es 1.77.1 veces más alto. A raíz de ello se ven formatos cuadrados y rectangulares. 
        .cajon.color-acento-botones.p-4
          p.mb-0 Generalmente se ven  dos relaciones la 4:3 (los que se manejaban en televisión antigua) que en cine se expresaría como 1,33:1 y la 16:9 que vendría siendo 1,77:1. Esta medida resulta de dividir el ancho (4) por el alto (3). Si se tiene una resolución de 1280 px, que sería el ancho, y se quiere con formato de 16:9 se divide 1080 (ancho) / 1.777 = dará 720. (alto) es decir 1080 x 720px. Si se hace lo mismo, pero se quiere con un aspecto ratio de 4:3 con una resolución de 1280 px (ancho) lo dividido por 1.333, y da 960 px, es decir 1280 x 720 px. 

    
    .BG04.mb-4
      h4.text-white.mb-0 De igual forma existen otras como son:

    .row.mb-5
      .col-md-6.mb-5.mb-md-0
        LineaTiempoD.color-primario
          p(numero="1" titulo="Relación aspecto 1:1:") Significa que la altura y el ancho son iguales, lo cual crea un cuadrado visualmente, una de las resoluciones más comunes son 1080 x 1080 px, la típica imagen como foto de perfil de Instagram. También es muy común el uso de impresión fotográfica, pantallas de móviles, plataformas sociales, pero no se recomienda para televisión o formatos digitales  
          p(numero="2" titulo="Relación aspecto 3:2:") Es el formato estándar gracias a las cámaras filmadoras que utilizaban películas de 35 milímetros, representado en píxeles su tamaño común es de 1080 x 720 px.
          p(numero="3" titulo="Relación aspecto 4:3 (1.33:1):") Relación Aspecto 4:3 (1.33:1 px):
          p(numero="4" titulo="Relación aspecto 16:9 (1.77:1):") Este es el formato de pantalla estándar utilizado de televisión de alta definición, su tamaño más común en pixeles es 1920x1080 px y 1280 x 720 px.
          p(numero="5" titulo="Relación aspecto 21:9 (2.35:1):") Este es el formato más usado en cine, con una dimensión en píxeles de 2560 x 1080 px o 3440 x 1440 px tienen un formato de tamaño mucho más apaisado que el de 16:9.
      .col-md-6(data-aos="flip-right")
        img(src="@/assets/curso/tema1/img04.png").img-450.m-auto

    .bg_C01       
      p.mb-5 A continuación, en la figura 1 se puede observar una comparativa de relación de aspecto (<i>aspect ratio</i>) con una resolución de tamaño proporcional a 720 px, donde se logra apreciar que algunos formatos son cuadrados, rectangulares o muy apaisados: 
    
      .row.justify-content-center.mb-4
        .col-lg-10
          .titulo-sexto.color-secundario
            h5 Figura 1.
            span Relación Aspecto con resolución 720 px 
          figure.mb-5(data-aos="zoom-in")
            img(src="@/assets/curso/tema1/img05.svg")
      
      p.mb-4 La forma de exportar videos desde Blender varía en función a la plataforma en que se van a reproducir los proyectos audiovisuales, no es lo mismo exportar para redes sociales, que hacerlo para Blu-ray o pantalla grande, pero para todos los casos es importante y funcional, así que se hace necesario conocer los parámetros que debe ajustarse para ello:

      .row.justify-content-center.mb-4
        .col-lg-6
          SlyderF.mb-5(columnas="col-12")
            .BG02.p-4
              figure.mb-4(data-aos="zoom-in")
                img(src='@/assets/curso/tema1/img05.png')
              p.text-center  Antiguamente con los televisores de caja, tenían un aspecto casi cuadrado, el cual era de 4:3, es decir que tenían 4 unidades de ancho por 3 de alto. 
            .BG02.p-4
              figure.mb-4(data-aos="zoom-in")
                img(src='@/assets/curso/tema1/img06.png')
              p.text-center  Pero ahora las pantallas de los últimos 20 años suelen ser de 16:9, que es el estándar por excelencia, lo que ha generalizado las emisiones televisivas, y el #[i streaming].  Este tipo de aspecto, tiene una visión panorámica.
            .BG02.p-4
              figure.mb-4(data-aos="zoom-in")
                img(src='@/assets/curso/tema1/img07.png')
              p.text-center Aun así, seguimos viendo en ellas, las famosas bandas de color negro alrededor de la imagen, con la finalidad de que las películas, que se han hecho con un aspecto diferente, puedan visualizarse de forma completa, pero perdiendo parte de pantalla en ella. 

      .row.justify-content-center.mb-4
        .col-lg-10
          .row.align-items-center.BG03.p-3
            .col-auto.d-none.d-lg-flex
              img(src='@/assets/curso/tema1/img08.png').img65
            .col
              h4 <i>Aspect ratio</i>
              p En los siguientes videos, podremos observar cómo ajustar los parámetros para realizar la salida de video desde Blender, ajustando el <i>aspect ratio</i>, <i>codec</i> y contenedor.
            .col-auto
              .row.flex-column
                .col-auto.mb-2    
                  a.boton.BG04.me-3(href="https://www.youtube.com/embed/HQDSwdRIVbo" target="_blank")
                    span.text-white Video 1
                .col-auto
                  a.boton.BG04.me-3(href="https://www.youtube.com/embed/PuCPB6B2fYY" target="_blank")
                    span.text-white Video 2
  
    separador

    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="slide-right")
      h2 1.2 Tipos de Formato    

    .gradient-bg_02.mb-5  
      .row.align-items-center.py-4    
        .col-md-12.col-lg-6.mb-4.mb-md-0
          p.mb-5 Hay diversidad de formatos que se pueden utilizar para exportar e importar imágenes y videos, para que al reproducirlos dependiendo de la plataforma que se establezca para ello, se visualicen de manera óptima y correcta, entre ellos se va a encontrar los siguientes:
          #MapaGroup01.row.justify-content-center
            .col-3.col-lg-4(data-aos="zoom-in")
              a(href="#t1").linkcard
                .round--number
                  h2.mb-0 1
                h5.text-center Formatos de video
            .col-3.col-lg-4(data-aos="zoom-in")
              a(href="#t2").linkcard
                .round--number
                  h2.mb-0 2
                h5.text-center Formatos de imagen
            .col-3.col-lg-4(data-aos="zoom-in")
              a(href="#t3").linkcard
                .round--number
                  h2.mb-0 3
                h5.text-center Formatos para <br> redes sociales

        .col-md-6.d-none.d-lg-inline(data-aos="flip-right")
          figure.customfigure
            img(src='@/assets/curso/tema1/img_08.png').customimage

    
    .BG04.mb-4
      #t1.h4.text-white.mb-0 Formatos de video:
    
    p.mb-4 A continuación, se podrán observar los conceptos de los formatos de video existentes: 
    .row.mb-5
      .col-lg-5(data-aos="flip-left")
        figure.mb-5.mb-lg-0
          img(src="@/assets/curso/tema1/img_10.svg").m-auto.img450

      .col-lg-6.mb-5.mb-md-0
        LineaTiempoD.color-primario
          p(numero="1" titulo="Contenedor MP4:") Conservan alta calidad, manteniendo un tamaño reducido. Es de los más utilizados actualmente, se usa frecuentemente para compartir en línea, puede contener datos adicionales como subtítulos e imágenes estáticas. Es combinado generalmente con h.264 y h.265.
          p(numero="2" titulo="Contenedor AVI:") Formato de video posicionado y antiguo, tiende a generar archivos grandes, pero soportados por gran variedad de <i>códecs</i>. No es útil para la transmisión en línea.
          p(numero="3" titulo="Contenedor MKV:") Formato de video profesional de código abierto llamado Matroska en el cual se pueden almacenar anexados al canal de audio, varios tipos de subtítulos, varias pistas de audio.
          p(numero="4" titulo="Contenedor FLV:") Actualmente se ha reducido su uso, fue el formato más común en reproductores en línea, no se recomienda trabajar en este formato puesto que se ha terminado la compatibilidad para él.
          p(numero="5" titulo="Contenedor MOV:") Calidad alta pero limitada compatibilidad, además de generar archivos muy grandes. Ideal para archivar videos de alta calidad.
          p(numero="6" titulo="Contenedor WMV:") Este tipo de formato genera videos pequeños ideales para ser enviados por correo, como muestra de avances. Pierde calidad significativamente al ser archivos pequeños.
          p(numero="7" titulo="Contenedor DIVX/XviD:") <i>Codec</i> antiguo que aún circula, diseñado para tener calidad de video alta, pero a su vez tamaños de archivos grandes. Usado frecuentemente para el almacenamiento y transporte en discos duros.
          p(numero="8" titulo="H.264 (MPEG-4):") Formato muy usado, con pérdida de calidad, pero ampliamente compatible, de uso estandarizado para Blu-ray y servidores #[i web]. Se puede utilizar a tasas de <i>bits</i> tanto altas como bajas, se utiliza con contenedores .mp4 y .mov.

    .hr--line

    .row.mb-5
      .col-lg-8
        .BG04.mb-4
          #t2.h4.text-white.mb-0 Formatos de imagen:   

        p.mb-4 El formato hace referencia a la forma en que se almacenarán los datos que hacen parte de una imagen. Existen dos tipos de imágenes, los mapas de <i>bits (bitmaps)</i> o imágenes rasterizadas, que están conformadas por un conjunto de puntos diminutos conocidos como píxeles ordenados en una malla, a los cuales se les atribuye un color por medio de coordenadas, por lo que no se puede aumentar su tamaño sin que se disminuya su calidad, y los vectores, los cuales están formados por polígonos de puntos en vez de pixeles, por lo que se pueden redimensionar o escalar infinitamente ya que no pierden su calidad. 
        .cajon.color-acento-botones.p-4
          p.mb-0 Existen diferentes formatos en los cuales se pueden almacenar datos de imagen:

      .col-lg-4.d-none.d-lg-flex(data-aos="flip-right")
        img(src="@/assets/curso/tema1/img10.png", style="width:330px;").m-auto    

     
    .gradient-bg_03   
      .row.justify-content-center.mb-4
        .col-lg-7(data-aos="flip-left")
          figure.mb-5
            img(src="@/assets/curso/tema1/img09.svg").m-auto.img680

        .col-lg-5
          SlyderF.mb-5
            .tarjeta-1.p-4
              .row.justify-content-center.mb-4
                .col-lg-6
                  img(src='@/assets/curso/tema1/img11.svg').img90.m-auto
              h2.text-center JPEG/JPG:
              p.text-center Es uno de los formatos más comunes, usado generalmente en las cámaras fotográficas digitales que comprime los archivos manteniéndolos ligeros para que puedan ser fácilmente visualizados, compartidos y publicados en red; sin embargo, su principal inconveniente es que cada vez que el archivo se edita y se vuelve a guardar va perdiendo calidad, además no es apto para guardar texto, ilustraciones o gráficos simples.
            .tarjeta-1.p-4
              .row.justify-content-center.mb-4
                .col-lg-6
                  img(src='@/assets/curso/tema1/img12.svg').img90.m-auto
              h2.text-center GIF:
              p.text-center Es un formato de compresión sin pérdidas manteniendo los archivos ligeros, y es altamente compatible por lo que a menudo se usa para compartir principalmente, gráficos #[i web] sencillos y animaciones cortas sin sonido (GIF animados).
            .tarjeta-1.p-4
              .row.justify-content-center.mb-4
                .col-lg-6
                  img(src='@/assets/curso/tema1/img13.svg').img90.m-auto
              h2.text-center PNG:
              p.text-center Se trata de un formato de compresión diseñado para gráficos #[i web] usado como mejora del GIF, y al igual que éste, no presenta pérdidas de calidad al editarse, permitiendo archivos más grandes e imágenes más complejas con colores sólidos y líneas nítidas; a diferencia de los GIF, pueden contener un grado de transparencia brindando mayor flexibilidad al editar o crear imágenes y gráficos en la #[i web], aunque sin permitir la animación de los mismos, además solo admiten colores RGB y su compatibilidad es limitada.
            .tarjeta-1.p-4
              .row.justify-content-center.mb-4
                .col-lg-6
                  img(src='@/assets/curso/tema1/img14.svg').img90.m-auto
              h2.text-center BMP:
              p.text-center Se trata de un formato sin compresión o su tasa es demasiado baja, en el cual se registra cada píxel de la matriz que compone una imagen. Es altamente compatible por lo que anteriormente se utilizaba mucho en la edición de imágenes, aunque presenta un gran problema debido a que el tamaño de los archivos es enorme y por lo tanto, son muy pesados.
            .tarjeta-1.p-4
              .row.justify-content-center.mb-4
                .col-lg-6
                  img(src='@/assets/curso/tema1/img15.svg').img90.m-auto
              h2.text-center TIF/TIFF: 
              p.text-center Es un formato de compresión sin pérdidas, utilizado principalmente para datos de imagen sin procesar, lo que permite trabajar con imágenes de alta calidad y archivos de impresión ya que mantiene la resolución y la calidad; además, es altamente compatible con ordenadores permitiendo guardar varias imágenes y páginas en un mismo archivo. Las imágenes que se trabajan con este formato son bastante grandes ya que contienen más detalles, más colores, mayor calidad y resolución, por lo que, aunque, es un formato de compresión, los archivos quedan bastante pesados

    .hr--line

    .BG04.mb-4
      #t3.h4.text-white.mb-0 Formatos para redes sociales:      
    
    p.mb-5 Se verá a continuación el formato ideal para diversas redes sociales, teniendo en cuenta los siguientes parámetros:

    .row.justify-content-center
      .col-lg-10
        LineaTiempoD.color-primario
          .row(numero="A" titulo="Formato de video para YouTube: formato .mp4.")
            .col-auto.mt-3
              figure
                img(src='@/assets/curso/tema1/r1.svg', alt='Texto que describa la imagen').img90
            .col-12.col-lg.mt-3
              p #[strong Formato MPEG-2:] salida en codificación de audio: <i>Dolby</i> AC-3 o MPEG <i>Layer</i> II, <i>bits</i> de audio: 128 kbps o superior.
              p #[strong Formato MPEG-4:] <i>códec</i> de video: H.264, <i>Códec</i> de audio: AAC, <i>bits</i> de audio: 128 kbps o superior.
              p #[strong Duración] mínima: 33, velocidad de <i>frames</i>, debe ser igual al video original (24, 25 o 30 <i>frames</i>.) Sin aplicarle procesos de remuestreo.
              p #[strong Resolución:] La resolución mínima para videos en venta o alquiler es full HD 1920x1080, en relación aspecto 16:9, para videos gratis no hay restricción de resolución, pero lo ideal es que no sea menor a HD 1280x720 px.

          .row(numero="B" titulo="Formato de video para Instagram: ")
            p formato .mp4, <i>ratio</i> vertical 9:16,<i>ratio</i> horizontal 16:9, ratio 1:1 Cuadrada: 1080 x 1080 px - Horizontal: 1080 x 566 px - Vertical: 1080 x 1350 px.
            .col-auto.mb-4.mb-lg-0
              figure
                img(src='@/assets/curso/tema1/r2.svg', alt='Texto que describa la imagen').img90
            .col-12.col-lg
              p #[strong Stories:] 1080 x 1920 px.
              p #[strong Para IG de instagram] la resolución mínima debe ser de 720 píxeles, si dura hasta 10 minutos, el tamaño tope debe ser de 650 MB, los que llegan a la hora de duración tendrán un tope de 3.6GB. 
              p #[strong Instagram Ads:] 1:1 cuadrado, 1,91:1 horizontal, 4:5 vertical, 4GB, 120 segundos. 

          .row(numero="C" titulo="Formato de video para LinkedIn: formato .mp4.")
            .col-12
              p.mb-0 formato 1:1 resolución 1920 x 1920 píxeles para anuncios en video.
          
          .row(numero="D" titulo="Formato de vídeo para Pinterest: formato .mp4.")
            .col-12
              p.mb-0 Pinterest acepta todo tipo de formatos de video, pero para un óptimo resultado en su interfaz lo recomendable es que su formato sea de 1000 x 1500 pixeles.

          .row(numero="E" titulo="Formato de vídeo para TikTok: formato .mp4.")
            .col-12
              p.mb-0 Formato de 1080 x 1920 píxeles.

          .row(numero="F" titulo="Formatos para Facebook: ")
            P formato .mp4 o .mov. La relación aspecto puede variar, para cada uno de los apartados de Facebook, noticias, <i>marketplace</i>, <i>instream</i>, Stories. Entre ellos están los siguientes:
            .col-auto.mb-4.mb-lg-0
              figure
                img(src='@/assets/curso/tema1/r3.svg', alt='Texto que describa la imagen').img90
            .col-12.col-lg
              p #[strong 16:9], <i>ratio</i> horizontal: 1920 x 1080 px.
              p #[strong 1:1] <i>ratio</i> cuadrado: 1080 x 1080 px.
              p #[strong 4:5] <i>ratio</i> Vertical: 864 x 1080 px.
              p.mb-0 #[strong 9:16] 1080 x 1920 px. 

          .row(numero="G" titulo="Formato de video para Twitter:")
            .col-auto.mb-4.mb-lg-0
              figure
                img(src='@/assets/curso/tema1/r4.svg', alt='Texto que describa la imagen')
            .col-12.col-lg
              P 1280 x 1024 px
              p.mb-0 #[strong #[i Aspect ratio]:] <br>1:2,39 -2,39:1.

</template>

<script>
export default {
  name: '1FormatosYExportaciN',
  components: {},
  data: () => ({
    indicadorImagenZoom: true,
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
