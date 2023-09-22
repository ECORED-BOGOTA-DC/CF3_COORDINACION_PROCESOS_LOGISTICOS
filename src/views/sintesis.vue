<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    p(data-aos="fade-right") La atención al cliente en los procesos logísticos implica brindar un trato personalizado, eficiente y oportuno a lo largo de todas las etapas, desde la recepción de pedidos hasta la entrega final. Esto incluye una comunicación clara, seguimiento de las solicitudes del cliente, resolución de problemas y garantizar la puntualidad en la entrega de los productos.
    p.mb-5(data-aos="fade-right") En resumen, la atención y servicio al cliente son fundamentales en una empresa, con un enfoque en la planificación estratégica, la fidelización, la medición y la satisfacción del cliente. Para lograrlo, es necesario contar con una cultura corporativa sólida y estrategias organizacionales flexibles que se adapten a las necesidades tanto de los clientes como de los proveedores. Al revisar estos temas, se puede observar el siguiente esquema.

    .row.justify-content-center
      .col-lg-10.mb-5(data-aos="fade-right")
        figure
          img(src="@/assets/curso/temas/sintesis.svg", alt="Representa la síntesis del componente formativo Atención y servicio al cliente, teniendo en cuenta el cliente, la medición, planeación estratégica servicio al cliente y trazabilidad y el desarrollo de cada una de estas.")
      .col-auto(data-aos="fade-left")
        a.anexo.mb-4(:href="obtenerLink('/downloads/sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
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
