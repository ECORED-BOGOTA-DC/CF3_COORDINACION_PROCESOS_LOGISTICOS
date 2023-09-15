<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 6
      h1 Medición del servicio al cliente

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-6.order-lg-1.order-2(data-aos="fade-right")
        p La medición no es del servicio como tal, lo que se recomienda medir es la satisfacción del cliente que sirve como punto de referencia para la corrección y la formación de la política postventa de la empresa y también determina el nivel de satisfacción de los clientes permitiendo identificar sus oportunidades, habilidades, debilidades para hacer los cambios necesarios en busca de fidelizar al público existente y atraer nuevos prospectos.
        .cajon1.color-primario1.p-4
          p.mb-0 Las organizaciones deben orientarse hacia sus clientes adaptando de manera continua el producto o servicio ofertado a los deseos de sus clientes con el objetivo de conseguir su satisfacción y fidelización. Para ello, es muy importante conocer cuáles son sus requerimientos y analizar el grado de cumplimiento de los mismos, la medición de la satisfacción del cliente debe ser considerada como un proceso más que la empresa debe integrar dentro del sistema de gestión de la organización y garantizar su realización de forma periódica y eficientemente.
      .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
        figure
          img(src='@/assets/curso/img55.svg', style="width: 550px; margin: auto;" alt="Imagen decorativa")
    
    separador
    #t_6_1.titulo-segundo.color-acento-botones(data-aos="fade-right")
      h2 6.1 Satisfacción del cliente

    p.mb-5(data-aos="fade-right") La satisfacción del cliente es el pilar básico de cualquier negocio, son los principales métodos o herramientas que las empresas pueden utilizar para medir la satisfacción de sus clientes, acá se exponen algunos de ellos:
    
    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta BG01" data-aos="zoom-in")
      .row(titulo="Encuestas")
        .col
          p La encuesta de satisfacción es el método más clásico y utilizado para conocer qué piensan los clientes de nuestra organización. Se utilizan preguntas que deberían estar enfocadas a la experiencia de compra, capacidad que tiene nuestro producto/servicio para resolver los problemas o necesidades, calidad del producto o servicio entregado, cumplimiento de plazos en la entrega del producto/servicio, cualquier otra valoración acerca de nuestra marca.
          p Existen diferentes tipos de encuestas como:
          ul.lista-ul
            li 
              i.fas.fa-angle-right(style="color: #FE7062")
              span #[b Encuestas de satisfacción a clientes reales históricos: ]
                |consiste en la realización de encuestas mediante cuestionarios de satisfacción a tres tipos de clientes: clientes nuevos, clientes que están reduciendo su volumen de compra y clientes que han dejado de consumir nuestro producto.
            li 
              i.fas.fa-angle-right(style="color: #FE7062")
              span #[b Encuestas de satisfacción: ]
                |consiste en realizar encuestas de satisfacción mediante cuestionarios cortos a clientes de la empresa seleccionados a partir de criterios objetivos previamente definidos que nos permitan obtener la opinión de nuestros clientes con posterioridad a la compra del producto o servicio.
            li 
              i.fas.fa-angle-right(style="color: #FE7062")
              span #[b Encuestas telefónicas: ]
                |antes de realizar una entrevista telefónica, debemos preguntarle al cliente si tiene tiempo de responderla.
            li 
              i.fas.fa-angle-right(style="color: #FE7062")
              span #[b Encuestas al personal: ]
                |en los casos en que determinados empleados estén en contacto directo con el cliente, podemos realizar encuestas a estos empleados con el fin de obtener una información directa sobre su opinión.
      div(titulo="Quejas y sugerencias")
        .row.align-items-start
          .col
            p.mb-0 Establecer un sistema de recogida de quejas y sugerencias es un método básico para recopilar información. Las quejas son oportunidades de mejora.
      div(titulo="Investigaciones de mercado")
        .row.align-items-start
          .col
            p.mb-0 Se trata de investigaciones sobre la totalidad de consumidores reales y potenciales de nuestros productos o servicios con el fin de evaluarlos con los ofrecidos por la competencia para identificar oportunidades y amenazas.
      div(titulo="Paneles de clientes")
        .row.align-items-start
          .col
            p.mb-0 Se selecciona un grupo de clientes que conozcan muy bien nuestro producto o servicio para obtener sugerencias y opiniones sobre el mismo.
      div(titulo="Cliente oculto")
        .row.align-items-start
          .col
            p.mb-0 En este método de medición, un evaluador se hace pasar por cliente de la empresa y simula una compra para valorar los aspectos relacionados con la misma.
      div(titulo="Sesiones de grupo")
        .row.align-items-start
          .col
            p.mb-0 Se organizan reuniones con grupos reducidos de clientes centradas en aspectos muy concretos del producto o servicio.
      div(titulo="Entrevistas personales")
        .row.align-items-start
          .col
            p.mb-0 Son reuniones periódicas individuales con clientes seleccionados en las que se tratan una gran selección de aspectos relacionados con nuestro producto o servicio de una manera formal para poder identificar expectativas reales del cliente.
    
    separador
    #t_6_2.titulo-segundo.color-acento-botones(data-aos="fade-right")
      h2 6.2 Técnicas de evaluación del servicio

    p.mb-5(data-aos="fade-right") En las técnicas de medición y evaluación del servicio existen varios instrumentos que permiten consignar la percepción y satisfacción del cliente a diferentes escalas.
    
    .row.justify-content-center.mb-5 
      .col-10
        .titulo-sexto.color-acento-botones(data-aos="fade-right")
          h5 Tabla 1.
          span Técnicas de evaluación de servicio al cliente
        .tabla-a.color-acento-botones(data-aos="zoom-in")
          table
            caption Nota. Adaptado y modificado de Questionpro (2021).
            thead
              tr
                th Indicador
                th Cálculo
                th Objetivo
            tbody
              tr
                td.bg-color1 Satisfacción general
                td.bg-color1(rowspan="5") Las encuestas de satisfacción del cliente son herramientas que te ayudan a comprobar los niveles de satisfacción.
                  p.mt-4 Se determina haciendo una pregunta a los clientes, “En una escala de 0-10 (donde 0 es el más bajo y 10 el más alto).
                td.bg-color1 Ayuda a comprender qué tan satisfechos se encuentran en general.
              tr
                td Número de quejas recibidas
                td Permite comprender las áreas de negocio que son un problema y resolverlo.
              tr
                td.bg-color1 Tasa de quejas no resueltas
                td.bg-color1 Optimiza los recursos y ofrece un horario flexible para la atención al cliente.
              tr
                td Tiempo para solución de quejas
                td Permite mejorar los tiempos de atención al cliente y aumenta la posibilidad de mantenerlos fieles a la empresa.
              tr
                td.bg-color1 Indicador Net Promoter Score
                td.bg-color1 Ofrece la posibilidad de conocer si el cliente está satisfecho con el servicio y recomendará a la empresa.
    
    separador
    #t_6_3.titulo-segundo.color-acento-botones(data-aos="fade-right")
      h2 6.3 Indicadores de gestión del servicio al cliente (medición del servicio)

    p(data-aos="fade-right") Los #[b indicadores de servicio] o #[b KPI] (#[i Key Performance Indicator]) permiten conocer la calidad de los productos o servicios que se comercializan en un mercado. La mejor forma de hacerlo es preguntando a los clientes sobre su nivel de satisfacción.
    p.mb-5(data-aos="fade-right") Mora (2008), indica que “Los KPI de servicio al cliente son métricas que se encargan de medir el rendimiento y la forma en la que el equipo enfoca el soporte y en la experiencia del consumidor y administra sus labores” (parr.3); estos elementos permiten unas mediciones que se pueden monitorear y analizar constantemente buscando identificar más oportunidades de mejora en busca de ofrecer la mejor experiencia a cada cliente.
    
    .h4 Beneficios de tener KPI de servicio al cliente
    
    .row.align-items-center.mb-5
      .col-lg-6
        p Entre los principales beneficios de contar con KPI de servicio al cliente se encuentran los siguientes:
        ul.lista-ul
          li(data-aos="fade-right")
            i.fas.fa-check(style="color: #FE7062")
            | Conocer el desempeño del equipo encargado del área de atención.
          li(data-aos="fade-right") 
            i.fas.fa-check(style="color: #FE7062")
            | Tomar mejores decisiones para tu negocio.
          li(data-aos="fade-right") 
            i.fas.fa-check(style="color: #FE7062")
            | Conseguir clientes fieles a tu marca.
          li(data-aos="fade-right") 
            i.fas.fa-check(style="color: #FE7062")
            | Conocer los elementos que conforman tu servicio para cubrir las necesidades de tus clientes.
          li(data-aos="fade-right") 
            i.fas.fa-check(style="color: #FE7062")
            | Crear estrategias de impacto para los clientes.
          li(data-aos="fade-right") 
            i.fas.fa-check(style="color: #FE7062")
            | Disminuir los tiempos de servicio a clientes y resolución de problemas.
      .col-lg-6.col-10.order-lg-2.order-1.mb-lg-0.mb-4(data-aos="fade-left")
        figure
          img(src='@/assets/curso/img56.svg', style="width: 550px; margin: auto;" alt="Imagen decorativa")

    
    .row.justify-content-center.mb-5 
      .col-10
        .titulo-sexto.color-acento-botones(data-aos="fade-right")
          h5 Tabla 2.
          span Indicadores de servicio al cliente
        .tabla-a.color-acento-botones(data-aos="zoom-in")
          table
            caption Nota. Adaptado y modificado de Questionpro (2021).
            thead
              tr
                th Indicador
                th Cálculo
                th Objetivo
            tbody
              tr
                td.bg-color1 Nivel de cumplimiento entregas a clientes
                td.bg-color1 Total de pedidos no entregados a tiempo / Total de pedidos despachados
                td.bg-color1 Calcular el porcentaje real de las entregas oportunas y efectivas a los clientes.
              tr
                td Calidad del servicio
                td Personal no adecuado / Personal adecuado
                td Establece un estándar en la atención al cliente.
              tr
                td.bg-color1 Indicador de rotación al cliente
                td.bg-color1 Número de clientes perdidos / Número total de clientes(periodo) X 100
                td.bg-color1 Mide cuando las personas dejan de comprar productos o de utilizar los servicios de una marca.
              tr
                td Nivel de servicio
                td Llamadas atendidas antes de x segundos / Llamadas recibidas
                td Permite conocer la percepción de servicio respecto a las llamadas de los clientes.
              tr
                td.bg-color1 Tasa de retención de clientes
                td.bg-color1 Número de clientes al final del periodo - Número de nuevos clientes / Número de clientes al inicio del periodo X 100
                td.bg-color1 Ayuda a conocer si los clientes se encuentran contentos con el servicio y se mantendrán fieles a la marca.
    
    separador
    #t_6_4.titulo-segundo.color-acento-botones(data-aos="fade-right")
      h2 6.4 Sistemas de Gestión de Calidad - ISO 9001

    p(data-aos="fade-right") Normas ISO (2021). La norma internacional ISO 9001 está enfocada a la consecución de la calidad en una organización mediante la implementación de un método o Sistema de Gestión de la Calidad (SGC). Esta norma se ha convertido desde el año 2002 en un referente de la calidad a nivel mundial. 
    p.mb-4(data-aos="fade-right") En la norma ISO 9001 se establecen los requisitos de un Sistema de Gestión de la Calidad, que permiten a una empresa demostrar su capacidad de satisfacer los requisitos del cliente, de los proveedores y los diferentes colaboradores, el certificado ISO 9001 es el certificado de la norma ISO más común y reconocida a nivel nacional e internacional.
    
    .row.justify-content-center.mb-5
      .col-lg-8(data-aos="zoom-in")
        .titulo-sexto.color-acento-botones(data-aos="fade-right")
          h5 Figura 4.
          span Mejora continua
        figure(data-aos="zoom-in")
          img(src='@/assets/curso/img57.svg', alt="Imagen decorativa")
          figcaption.mt-4 Nota. Modificado de Normas ISO (2021).
    
    p(data-aos="fade-right") La implementación de una ISO 9001 es, sin duda, una estrategia de diferenciación de una empresa con respecto a las demás y aventajar a la competencia en un mercado competitivo, demostrando que la gestión de la empresa se rige por los estándares de calidad que incorpora la Norma ISO 9001.
    p.mb-4(data-aos="fade-right") Beneficios de la aplicación de ISO en una empresa:
    
    ul.lista-ul.mb-5
      li(data-aos="fade-right")
        i.fas.fa-check(style="color: #FE7062")
        | Eficiencia en los procesos o actividades de la empresa. (Mejora de costes).
      li(data-aos="fade-right")
        i.fas.fa-check(style="color: #FE7062")
        | Mejora sustancial en la satisfacción de los clientes.
      li(data-aos="fade-right")
        i.fas.fa-check(style="color: #FE7062")
        | Herramienta de comunicación para mejorar la imagen de la empresa/marca.
      li(data-aos="fade-right")
        i.fas.fa-check(style="color: #FE7062")
        | Aumento del acceso al mercado, sin límites de fronteras.
      li(data-aos="fade-right")
        i.fas.fa-check(style="color: #FE7062")
        | Mejora de la comunicación interna, satisfacción de los trabajadores.
    
    separador
    #t_6_5.titulo-segundo.color-acento-botones(data-aos="fade-right")
      h2 6.5 Mejora continua

    p.mb-5(data-aos="fade-right") La mejora continua del servicio es la acción continua de todo sistema de gestión para lograr los objetivos deseados y hace parte de las herramientas básicas para aumentar la competitividad en las organizaciones.
    
    .row.justify-content-center.mb-5
      .col-10(data-aos="flip-up")
        .cajon1.color-primario1.p-4
          p.mb-0 Y basados en el contexto que dan Marín-García, Bautista-Poveda, & García-Sabater (2014), se entiende que la mejora continua es un proceso planificado, organizado y sistemático de cambios incrementales en los procesos productivos, en los sistemas o en las prácticas de trabajo, que permiten mejorar algún indicador de rendimiento. Es aplicable en todo tipo de empresas y está basada en el ciclo de Deming, compuesto por cuatro fases: estudiar la situación actual y recoger los datos necesarios para proponer las sugerencias de mejora; poner en marcha las propuestas seleccionadas a modo de prueba; comprobar si la propuesta ensayada está proporcionando los resultados esperados; implementar y estandarizar la propuesta con las modificaciones necesarias.
    
    p.mb-5(data-aos="fade-right") Para ayudar a estos procesos complejos existen herramientas de mejora que facilitan el entendimiento del ciclo y sus partes, es por eso que existe el ciclo de Deming que es un proceso metodológico que tiene como objetivo aplicar a un proceso cualquiera una acción cíclica formada por cuatro pasos fundamentales Plan, Do, Check y Act. De igual manera, se le conoce como espiral de mejora continua o ciclo PHVA, debido a sus etapas Planificar, Hacer, Verificar y Actuar; como se puede apreciar en el siguiente gráfico:
    
    .row.mx-0.mb-5
      .col-lg-3.col-6.px-2.py-5.bg-colo2.mb-lg-0.mb-4(data-aos="fade-right")
        figure
          img(src='@/assets/curso/img58.svg', style="width: 80px;" alt="Imagen decorativa")
        .h4.mt-3.mb-5 Planificar
        p.mt-5 Involucrar a la gente correcta.
        p Recopilar los datos disponibles.
        p Comprender las necesidades de los clientes.
        p Estudiar exhaustivamente el/los procesos involucrados.
        p ¿Es el proceso capaz de cumplir las necesidades?
        p Desarrollar el plan/entrenar al personal.
      .col-lg-3.col-6.px-2.py-5.bg-colo2.mb-lg-0.mb-4(data-aos="flip-right")
        figure
          img(src='@/assets/curso/img58.svg', style="width: 80px;" alt="Imagen decorativa")
        .h4.mt-3.mb-5 Hacer
        p.mt-5 Implementar la mejora/verificar las causas de los problemas.
        p Recopilar los datos apropiados.
      .col-lg-3.col-6.px-2.py-5.bg-colo2(data-aos="flip-left")
        figure
          img(src='@/assets/curso/img58.svg', style="width: 80px;" alt="Imagen decorativa")
        .h4.mt-3.mb-5 Verificar
        p.mt-5 Analizar y desplegar los datos.
        p ¿Se han alcanzado los resultados deseados?
        p Comprender y documentar las diferencias.
        p Revisar los problemas y errores.
        p ¿Qué se aprendió?
        p ¿Qué queda aún por resolver?
      .col-lg-3.col-6.px-2.py-5.bg-colo2(data-aos="fade-left")
        figure
          img(src='@/assets/curso/img58.svg', style="width: 80px;" alt="Imagen decorativa")
        .h4.mt-3.mb-5 Actuar
        p.mt-5 Incorporar la mejora al proceso.
    
    p(data-aos="fade-right") Este elemento de mejora continua se debe aplicar cada vez que se pueda en cada proceso de la empresa, por eso precisamente se llama “ciclo” porque #[b no se detiene nunca] mientras la empresa esté trabajando.

</template>

<script>
export default {
  name: 'Tema6',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped></style>
