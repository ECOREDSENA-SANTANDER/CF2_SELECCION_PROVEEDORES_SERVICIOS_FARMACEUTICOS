<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Negociación con proveedores en el contexto farmacéutico colombiano 

    .row.justify-content-center.mb-3(data-aos="zoom-in-left")
      .col-lg-1.d-none.d-lg-block
        img(src='@/assets/curso/Tema2/img02.svg', alt='')
      .col-lg-11
        p En Colombia, la negociación con proveedores farmacéuticos se desarrolla dentro de un marco normativo y técnico que exige transparencia, trazabilidad y estándares de calidad. Existen diversos tipos de negociación que deben ajustarse a la naturaleza del comprador (Empresa Social del Estado - ESE, Institución Prestadora de Servicios de Salud - IPS, Entidad Promotora de Salud - EPS o droguería) y del proveedor:
    
    .row.justify-content-center(data-aos="flip-up")  
      .col-lg-4.col-md-6.mb-4
        .overflow-hidden.h-100.cambiartarjeta.p-4(data-aos="fade-left")
          img.img-a.img-t.mb-3(src='@/assets/curso/Tema2/1.svg', alt='tema1')
          .p-2.mb-4
            h4.text-center.bg0.p-2 Negociación distributiva
            p.text-center Común en contrataciones puntuales o situaciones de urgencia, donde cada parte busca maximizar sus propios intereses. Se presenta con frecuencia en adquisiciones directas por menor cuantía o emergencia sanitaria.
      
      .col-lg-4.col-md-6.mb-4
        .overflow-hidden.h-100.cambiartarjeta.p-4(data-aos="fade-left")
          img.img-a.img-t.mb-3(src='@/assets/curso/Tema2/2.svg', alt='tema1')
          .p-2.mb-4
            h4.text-center.bg0.p-2 Negociación integrativa
            p.text-center Propicia acuerdos de largo plazo que favorecen a ambas partes, como convenios marco entre EPS e IPS. Se busca optimizar calidad y reducir costos mediante compromisos colaborativos.
      
      .col-lg-4.col-md-6.mb-4
        .overflow-hidden.h-100.cambiartarjeta.p-4(data-aos="fade-left")
          img.img-a.img-t.mb-3(src='@/assets/curso/Tema2/3.svg', alt='tema1')
          .p-2.mb-4
            h4.text-center.bg0.p-2 Negociación mixta
            p.text-center Es la más frecuente, ya que integra criterios técnicos, normativos y económicos. Permite asegurar la calidad del producto y el cumplimiento regulatorio, mientras se gestionan eficientemente los recursos disponibles.

      p Estos enfoques deben enmarcarse en la Ley 80 de 1993 y la Ley 1150 de 2007, que establecen principios de eficiencia, transparencia y responsabilidad en la contratación.

      .row.justify-content-start.mb-4(data-aos="zoom-in-left")
        .col-sm-12.col-lg-7
          .d-flex.align-items-center.mt-4
            img.w-card-icon(src="@/assets/curso/Tema1/ico.svg")
            h3.bg2.py-2.w-card-text Seleccionar estrategias de negociación


      p La elección de estrategias de negociación en el sector farmacéutico colombiano debe contemplar aspectos normativos, técnicos, comerciales y operativos. Estas estrategias buscan acuerdos sostenibles que garanticen calidad, cumplimiento legal y eficiencia económica.

      .row.justify-content-start.mb-4(data-aos="zoom-in-left")
        .col-sm-12.col-lg-7
          .d-flex.align-items-center.mt-4
            h3.bg4.py-2.w-card-text2 Estrategias clave 

      .row.justify-content-center.align-items-center.mb-3
        .col-lg-8
          AcordionA(tipo="b" clase-tarjeta="tarjeta tarjeta--azul")
            .row(titulo="Investigación previa del proveedor")
              .col-md-12.mb-4.mb-md-0
                p Implica revisar antecedentes en plataformas como SECOP, validar registros del Instituto Nacional de Vigilancia de Medicamentos y Alimentos (INVIMA), revisar sanciones, y consultar referencias en otras entidades.
            .row(titulo="Comparación de múltiples ofertas")
              .col-md-12.mb-4.mb-md-0
                p Antes de negociar, deben establecerse requisitos como BPM, BPA, ISO, registro sanitario, y trazabilidad, conforme a la Resolución 1403 de 2007.
            .row(titulo="Ofrecimiento de incentivos")
              .col-md-12.mb-4.mb-md-0
                p Pueden incluir descuentos por volumen, renovaciones automáticas, reducción de penalidades por buen desempeño o soporte adicional.
            .row(titulo="Formalización documental")
              .col-md-12.mb-4.mb-md-0
                p Todas las etapas de la negociación deben quedar documentadas en actas, minutas y expedientes técnicos, garantizando trazabilidad y cumplimiento.
        .col-lg-4
          img(src='@/assets/curso/Tema2/img01.png', alt='')

      .row.justify-content-start.mb-4(data-aos="zoom-in-left")
        .col-sm-12.col-lg-7
          .d-flex.align-items-center.mt-4
            h3.bg4.py-2.w-card-text2 Negociar con proveedores 

      .row.justify-content-center.mb-2
        .col-lg-6.mb-3
          img(src='@/assets/curso/Tema2/img02.png', alt='')
        .col-lg-6
          p.mb-3 La negociación con proveedores farmacéuticos en Colombia representa un proceso estratégico que debe alinearse con criterios técnicos, normativos, financieros y éticos. Su impacto en la salud pública exige rigurosidad en cada etapa del proceso.
          .row.justify-content-center.align-items-center.bg1.p-2
            .col-lg-2
              img(src='@/assets/curso/Tema2/cuaderno.svg', alt='')
            .col-lg-10
              p #[b Cumplimiento normativo:] debe regirse por leyes como la Ley 100 de 1993, Resolución 1403 de 2007 y normativas del INVIMA. En entidades públicas aplica además la Ley 80 de 1993, Ley 1150 de 2007 y el Decreto 1082 de 2015. El incumplimiento puede derivar en sanciones por parte de la Superintendencia Nacional de Salud.


      .row.justify-content-start.mb-5(data-aos="zoom-in-left")
        .col-sm-12.col-lg-7
          .d-flex.align-items-center.mt-4
            h3.bg4.py-2.w-card-text2 Buenas prácticas de negociación


      SlyderF(columnas="col-lg-6 col-xl-4")
        .tarjeta.fondo_tarjeta.p-4
          .row.justify-content-center.mb-3
            .col-8.col-lg-6
              img(src='@/assets/curso/Tema2/01.svg' alt='')
          p #[b 1. Establecer condiciones claras:] tiempos de entrega, condiciones de almacenamiento, cobertura territorial, vida útil del producto.

        .tarjeta.fondo_tarjeta.p-4
          .row.justify-content-center.mb-3
            .col-8.col-lg-6
              img(src='@/assets/curso/Tema2/02.svg' alt='')
          p #[b 2. Verificar documentación del proveedor:] registro sanitario, certificaciones BPM / BPA, fichas técnicas, experiencia previa, y capacidad de respuesta.

        .tarjeta.fondo_tarjeta.p-4
          .row.justify-content-center.mb-3
            .col-8.col-lg-6
              img(src='@/assets/curso/Tema2/03.svg' alt='')
          p #[b 3. Considerar más allá del precio:] soporte técnico, garantías, logística y políticas de devolución.

        .tarjeta.fondo_tarjeta.p-4
          .row.justify-content-center.mb-3
            .col-8.col-lg-6
              img(src='@/assets/curso/Tema2/04.svg' alt='')
          p #[b 4. Documentar el proceso:] actas firmadas, matrices comparativas, justificaciones técnicas y registros contractuales. 










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
