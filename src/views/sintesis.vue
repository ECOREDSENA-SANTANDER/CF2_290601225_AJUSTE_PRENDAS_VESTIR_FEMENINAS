<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    p A continuación, se presenta el organigrama que resume los elementos fundamentales relacionados con las máquinas, herramientas e insumos en el ajuste de prendas femeninas. Está organizado en cuatro bloques principales: el primero aborda la maquinaria utilizada en la confección de prendas, incluyendo tipos, niveles de uso y sus complementos; el segundo agrupa las herramientas propias de la modistería, clasificadas en funciones de medición, trazado, ensamblaje y acabados; el tercero se refiere a los insumos empleados, como hilos, entretelas, cintas, elásticos, materiales decorativos y de refuerzo; y el cuarto bloque contempla el manejo de máquinas y la organización del espacio de trabajo.  

    .tarjeta.tarjeta--gris.mb-5.p-4
      .row.justify-content-center
        .col-lg-11
          figure
            img(src="@/assets/curso/sintesis.svg", alt="El esquema organiza los componentes clave involucrados en el ajuste de prendas femeninas, agrupándolos en cuatro categorías principales: maquinaria en la confección, herramientas de modistería, insumos en la modistería y manejo de máquinas y espacio de trabajo. Cada categoría se divide en subtemas específicos. En maquinaria se detallan los tipos de máquinas, tanto familiares como semiindustriales, y sus complementos. Las herramientas de modistería se clasifican según su función: medición, trazado, corte, ensamblaje y acabados. Los insumos incluyen hilos, entretelas, estabilizadores, elementos para plackets, cintas, elásticos, materiales decorativos y de refuerzo. Finalmente, se aborda el manejo adecuado del entorno y de las máquinas para garantizar eficiencia y seguridad.")
    .row.justify-content-center
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/bullets/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
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
