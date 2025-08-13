<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Insumos en la modistería

    .bloque-texto-g.bloque-texto-g--inverso.color-primario.p-3.p-sm-4.p-md-5.mb-4(data-aos="fade-down")
      .bloque-texto-g__img(:style="{'background-image':`url(${require('@/assets/curso/temas/t3/1.png')})`}")
      .bloque-texto-g__texto.p-4
        p.mb-0 Los insumos son los materiales esenciales para confeccionar una prenda. Su elección influye en la calidad, apariencia y durabilidad del producto final.#[br] #[br]
        p Las telas pueden ser naturales (como algodón o lino) o sintéticas (como poliéster o nylon), y se seleccionan según el tipo de prenda y el uso previsto. Los hilos, por su parte, unen las piezas: se usa algodón para acabados suaves y poliéster cuando se requiere mayor resistencia.#[br] #[br]
        p Entre los insumos de soporte, las entretelas y estabilizadores refuerzan áreas como cuellos y puños, mientras que cierres, botones y velcros permiten ajustar y decorar. Otros elementos como cintas al bies, elásticos y cintas de refuerzo ayudan a dar forma y rematar bordes.

    .row.justify-content-center.align-items-center(data-aos="fade")
      .col-lg-3.col-md-5
        .bg-1.tarjeta.p-4.mb-4.mb-lg-0
          p.mb-0 #[strong Cinta al bies:] tira de tela cortada en diagonal, flexible, usada para rematar bordes curvos o rectos con buen acabado.
      .col-lg-4.col-md-7
        p También se utilizan accesorios decorativos como encajes o pasamanerías, que aportan estilo, y productos de mantenimiento como sprays de marcado o lubricantes, que facilitan el proceso de confección.
      .col-lg-2.col-md-4.col-4
        img(src='@/assets/curso/temas/t3/2.svg', alt='')
      .col-lg-3.col-md-8.col-8
        .bg-10.tarjeta.p-4
          p.mb-0 Una adecuada selección de insumos permite confeccionar prendas funcionales, cómodas y con un acabado estético de calidad.


    Separador
    #t_3_1.titulo-segundo.color-acento-contenido(data-aos='fade-right')
      h2 3.1.	Hilos

    .row.justify-content-center.align-items-center.mb-5(data-aos="fade")
      .col-lg-5
        img(src='@/assets/curso/temas/t3/3.png', alt='')
      .col-lg-4
        img.w-60.mb-3(src='@/assets/curso/temas/t3/4.svg', alt='')
        p El hilo es el material que da firmeza a las costuras, puede ser de algodón, ideal para prendas suaves y transpirables, o de poliéster, que se destaca por su resistencia y variedad de colores; también existen hilos especiales como los de núcleo combinado, que ofrecen fuerza y flexibilidad.
        .bg-6.tarjeta.p-4
          p.mb-0 Seleccionar el hilo adecuado garantiza una costura resistente, de buen acabado y coherente con las características de la prenda.
      .col-lg-3
        .titulo-sexto.color-acento-contenido.mb-2
          h5 Figura 27.
          span Estructura general del hilo
        figure.mb-3  
          img(src='@/assets/curso/temas/t3/fig27.png', alt='Tres filamentos cilíndricos están entrelazados en espiral, formando una hebra compacta con textura uniforme.')
        figcaption Fuente: 
          a(href="https://www.coats.com/es/info-hub/selecting-your-sewing-threads/" target="_blank") https://www.coats.com/es/info-hub/selecting-your-sewing-threads/

    TabsB.color-acento-contenido.mb-5(data-aos="fade-down")
      .py-4.py-md-5(titulo="El hilo monofilamento" :icono="require('@/assets/curso/temas/t3/tab-ico1.svg')")
        .row.justify-content-center
          .col-md-11
            .row.justify-content-center.align-items-center.mb-3
              .col-lg-4
                .titulo-sexto.color-acento-contenido.mb-2
                  h5 Figura 28.
                  span Hilo con núcleo
                figure.mb-3  
                  img(src='@/assets/curso/temas/t3/fig28.png', alt='Tres hebras trenzadas forman una estructura externa que recubre un núcleo central compuesto por varios filamentos delgados alineados verticalmente.')
                figcaption Fuente: 
                  a(href="https://www.coats.com/es/info-hub/selecting-your-sewing-threads/" target="_blank") https://www.coats.com/es/info-hub/selecting-your-sewing-threads/
              .col-lg-8
                p El hilo con núcleo combina un filamento de poliéster en el centro con un recubrimiento de fibras (algodón o poliéster), lo que le aporta resistencia y suavidad. Esta estructura facilita el paso por la máquina y produce costuras firmes, ideales para confección a alta velocidad y prendas de alto esfuerzo. Por su parte, los hilos de filamento continuo (como poliéster, nylon o acetato) ofrecen mayor resistencia que los de fibra corta y se utilizan en aplicaciones industriales por su durabilidad y uniformidad.
            .row.justify-content-center.align-items-center
              .col-lg-8
                h4 El hilo monofilamento 
                p Consiste en un solo filamento continuo de diámetro controlado, lo que le confiere una resistencia y uniformidad destacadas a un coste de producción relativamente bajo. Sin embargo, su rigidez y textura áspera limitan su flexibilidad y confort, por lo que su aplicación se concentra principalmente en confecciones donde estas propiedades resultan deseables, tales como bastillas, cortinas y tapicería. Gracias a su consistencia dimensional y su estabilidad frente a la tensión, el monofilamento garantiza bordes definidos y duraderos en usos decorativos y de tapizado, aunque no se recomienda para prendas de vestir que requieran suavidad o elasticidad.
              .col-lg-4
                .titulo-sexto.color-acento-contenido.mb-2
                  h5 Figura 29.
                  span Hilo monofilamento
                figure.mb-3  
                  img(src='@/assets/curso/temas/t3/fig29.png', alt='Cilindro continuo con superficie lisa y uniforme, sin divisiones visibles ni textura trenzada.')
                figcaption Fuente: 
                  a(href="https://www.coats.com/es/info-hub/selecting-your-sewing-threads/" target="_blank") https://www.coats.com/es/info-hub/selecting-your-sewing-threads/
      .py-4.py-md-5(titulo="El hilo multifilamento suave" :icono="require('@/assets/curso/temas/t3/tab-ico2.svg')")
        .row.justify-content-center
          .col-md-11
            .row.justify-content-center.align-items-center
              .col-lg-4
                .titulo-sexto.color-acento-contenido.mb-2
                  h5 Figura 30.
                  span Hilo multifilamento
                figure.mb-3  
                  img(src='@/assets/curso/temas/t3/fig30.png', alt='Cilindro compuesto por múltiples hilos finos enrollados en espiral alrededor de un núcleo central, generando un patrón de textura densa.')
                figcaption Fuente: 
                  a(href="https://www.coats.com/es/info-hub/selecting-your-sewing-threads/" target="_blank") https://www.coats.com/es/info-hub/selecting-your-sewing-threads/
              .col-lg-8
                p Se fabrica principalmente a partir de filamentos continuos de nylon o poliéster torcidos en conjunto, lo que le confiere una resistencia excepcional. Esta construcción, que integra dos o más hilos finos en un único cordón, garantiza una alta tenacidad y flexibilidad, atributos esenciales para aplicaciones sometidas a elevados esfuerzos mecánicos. Por ello, resulta idóneo para la confección de calzado, artículos de cuero y productos industriales, donde la durabilidad de la costura es prioritaria. Además, su superficie suave reduce el desgaste del material base y facilita el deslizamiento por las máquinas de coser, contribuyendo a un proceso de alta productividad y calidad constante.
      .py-4.py-md-5(titulo="El hilo de filamento texturizado" :icono="require('@/assets/curso/temas/t3/tab-ico3.svg')")
        .row.justify-content-center
          .col-md-11
            .row.justify-content-center.align-items-center
              .col-lg-4
                .titulo-sexto.color-acento-contenido.mb-2
                  h5 Figura 31.
                  span Hilo de filamento texturizado
                figure.mb-3  
                  img(src='@/assets/curso/temas/t3/fig31.png', alt='Dos haces de filamentos con estructura alargada se enrollan entre sí generando una torsión visible, con texturas internas marcadas y acabado fibroso.')
                figcaption Fuente: 
                  a(href="https://www.coats.com/es/info-hub/selecting-your-sewing-threads/" target="_blank") https://www.coats.com/es/info-hub/selecting-your-sewing-threads/
              .col-lg-8
                p Se elabora a partir de filamentos continuos de poliéster sometidos a un proceso de texturización que incrementa su volumen y elasticidad. Se emplea principalmente como hilo de lanzadera en puntadas de cobertura, donde aporta un acabado más denso y una mayor capacidad de recuperación en zonas sometidas a estiramiento. Gracias a su estructura voluminosa, mejora la cobertura del pespunte y la extensibilidad de la costura; sin embargo, su mayor volumen y menor tensión superficial incrementan la tendencia al enredo, por lo que es imprescindible ajustar con precisión los parámetros de tensión y guía durante el cosido para asegurar la uniformidad y continuidad de la puntada.

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-9(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido
          h5 Tabla 
          span 
        .tabla-a.color-acento-contenido
          table(alt="")
            caption Fuente: SENA, (2025)
            thead
              tr.bg-color-primario
                th.w-25 
                th.text-center 
            tbody
              tr
                td 
      .col-lg-3(data-aos="fade-left")        
        img.d-none.d-lg-block(src="@/assets/curso/temas/t3/5.png")

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-3(data-aos="fade-right")        
        img.d-none.d-lg-block(src="@/assets/curso/temas/t3/6.png")
      .col-lg-9(data-aos="fade-left")
        .titulo-sexto.color-acento-contenido
          h5 Tabla 
          span 
        .tabla-a.color-acento-contenido
          table(alt="")
            caption Fuente: SENA, (2025)
            thead
              tr.bg-color-primario
                th.w-25 
                th.text-center 
                th.text-center 
            tbody
              tr
                td 
      



    Separador
    #t_3_2.titulo-segundo.color-acento-contenido(data-aos='fade-right')
      h2 


    .titulo-sexto.color-acento-contenido.mb-2
      h5 Figura 
      span 
    figure.mb-3  
      img(src='@/assets/curso/temas/t3/fig27.png', alt='')
    figcaption Fuente: 
      a(href="" target="_blank") 




    Separador
    #t_3_3.titulo-segundo.color-acento-contenido(data-aos='fade-right')
      h2 
    


    Separador
    #t_3_4.titulo-segundo.color-acento-contenido(data-aos='fade-right')
      h2 



    Separador
    #t_3_5.titulo-segundo.color-acento-contenido(data-aos='fade-right')
      h2 



    Separador
    #t_3_6.titulo-segundo.color-acento-contenido(data-aos='fade-right')
      h2 



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
