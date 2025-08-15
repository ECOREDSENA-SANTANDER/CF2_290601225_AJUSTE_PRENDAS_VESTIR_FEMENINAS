<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-6(data-aos="fade-right")
        p El componente dedicado a la “maquinaria, herramientas e insumos en modistería” se estructura en tres grandes bloques que articulan el conocimiento técnico con la aplicación práctica en el ajuste de prendas femeninas. En primer lugar, se analiza la maquinaria de confección, clasificada por su escala de uso, desde máquinas domésticas hasta equipos industriales, sumado a esto, se complementa con los accesorios que optimizan su rendimiento. Este apartado sitúa al aprendiz frente a los mecanismos y procesos que garantizan productividad, precisión y calidad en cada ciclo de costura.
        .row.justify-content-center.align-items-center.mb-4.mb-lg-0
          .col-lg-3.col-md-3.d-none.d-md-block
            img(src='@/assets/curso/temas/intro/2.svg', alt='')
          .col-lg-9.col-md-9
            p.mb-0 El segundo bloque, “herramientas de modistería”, profundiza en los instrumentos de medición, marcado, trazo, corte, ensamblaje y acabado. Todo ello para lograr una comprensión de la función y manejo de cintas métricas, reglas, tijeras, alfileres, prensatelas y planchas sientan las bases para realizar intervenciones y ajustes con exactitud y seguridad. 
      .col-lg-6(data-aos="fade-left")
        img(src='@/assets/curso/temas/intro/1.png', alt='')


    .row.bgc-intro.align-items-center.p-2.pt-5.p-md-3.pt-md-5(data-aos="fade")
      .col-lg-12.col-12.px-lg-4
        .row.justify-content-center.align-items-center

          .row.justify-content-center.align-items-center.mb-5 
            .col-lg-6
              .tarjeta.bg-1.p-4.mb-4.mb-lg-0
                p.mb-0 En el tercer bloque, “insumos en la modistería”, se estudian los materiales básicos y complementarios utilizados en la confección, como hilos, entretelas, cierres, botones, elásticos, adornos y refuerzos. Se abordan sus propiedades técnicas, usos específicos y criterios de selección, lo que permite al aprendiz identificar el insumo más adecuado según el tipo de tejido y el acabado deseado. Asimismo, se enseña a integrar cada insumo de manera coherente en el proceso de ajuste, asegurando la calidad, durabilidad y estética de la prenda.
            .col-lg-3.d-none.d-lg-block
              img(src='@/assets/curso/temas/intro/3.svg', alt='')
            .col-lg-3
              p A lo largo del desarrollo de los bloques formativos, se combinan explicaciones conceptuales, ejemplos y recomendaciones de buenas prácticas. Esta metodología busca fortalecer las competencias del futuro modista para que pueda responder con eficacia a las exigencias del sector textil-moda y mantener los estándares de calidad institucional del SENA.

          .row           
            .col-lg-12
              figure
                .video
                  iframe(width="560" height="315" src="https://www.youtube.com/embed/BV0fFtOsWuk?si=X4NxENRo3LLXAua_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
              figcaption Video. 


</template>

<script>
export default {
  name: 'Introduccion',
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
