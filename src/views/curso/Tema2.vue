<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'2. Alineación estrategia-estructura'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .bg-full-width.bg-h85.mb-5
      .px-4.px-md-5.pb-md-3
        .row.justify-content-center.align-items-center
          .col-lg-12
            .row.justify-content-center.align-items-center
              .col-lg-8(data-aos="fade-left").mb-3.mb-lg-0.text-white
                p En el ámbito empresarial, la estrategia es el conjunto de decisiones y acciones diseñadas para alcanzar objetivos organizacionales a largo plazo, asegurando una ventaja competitiva sostenible en un entorno dinámico y competitivo. 
                p.mb-0 Se basa en el análisis del entorno interno y externo de la organización, considerando factores como recursos, capacidades, competencia, tendencias del mercado y cambios tecnológicos.
              .col-lg-4(data-aos="zoom-in")
                img.img-fluid(src='@/assets/curso/tema2/1.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0

    #t_2_1.titulo-segundo(data-aos="flip-up")
      h2 #[span 2.1] ¿Qué es la estrategia empresarial?
    
    p.mb-4 La estrategia empresarial define como una empresa creará valor, competirá en su industria y logrará sus metas organizacionales, integrando elementos como la misión, visión, objetivos, posicionamiento y diferenciación en el mercado. Las estrategias pueden clasificarse en distintos niveles:

    .bg-full-width.bg-color-info.mb-5
      .p-4.p-md-5
        .row.justify-content-center.align-items-center.mb-5
          .col-lg-10
            ImagenInfografica.color-secundario
              template(v-slot:imagen)
                figure
                  img(src='@/assets/curso/tema2/2.svg', alt='', style="max-width: 1106px;").mx-auto
    
              .bg-color-white.box-shadow.p-3(x="8%" y="94%" numero="+")
                h5 Estrategia corporativa
                p Define el propósito general de la organización y cómo asigna recursos entre sus unidades de negocio.
    
              .bg-color-white.box-shadow.p-3(x="40%" y="6.5%" numero="+")
                h5 Estrategia de negocio
                p Se enfoca en la competencia dentro de un mercado específico, abordando aspectos como liderazgo en costos, diferenciación o enfoque.
    
              .bg-color-white.box-shadow.p-3(x="71%" y="94%" numero="+")
                h5 Estrategia funcional
                p Detalla cómo cada área de la empresa (<em>marketing</em>, producción, finanzas, recursos humanos) contribuye a la estrategia general.
    
    #t_2_2.titulo-segundo(data-aos="flip-up")
      h2 #[span 2.2] ¿Qué es la estrategia empresarial?
    
    p.mb-4 La estrategia organizacional, la estructura y la cultura son elementos fundamentales en el desarrollo y éxito de una empresa, ya que determinan la forma en que se establecen los objetivos y se gestionan los recursos para alcanzarlos.

    .bg-full-width.bg-color-5.mb-lg-5
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-8.order-2
            h2.mb-4(data-aos="flip-up") Alineación estrategia-estructura
            p.mb-4(data-aos="fade-right") En el PDF <b>Alineación estrategia-estructura</b>, se analizan las relaciones entre estos conceptos y su impacto en la dinámica empresarial, considerando cómo la alineación estratégica influye en la toma de decisiones y la eficiencia operativa. A lo largo del documento, se presentan enfoques y modelos clave que permiten comprender cómo las organizaciones pueden adaptarse a los cambios del entorno y fortalecer su cultura para mejorar su competitividad y sostenibilidad.
    
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_1.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Alineación estrategia-estructura.
    
          .col-lg-4.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema2/3.png', alt='')
              

    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.redalyc.org/articulo.oa?id=21209303 " target="_blank" rel="noopener noreferrer") Velásquez Vásquez, F. (2004). La estrategia, la estructura y las formas de asociación: Fuentes de ventaja competitiva para las pymes colombianas. Estudios Gerenciales, 20(93), 1-26. 
            
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://es.wikipedia.org/wiki/Cultura_organizacional?utm_source=chatgpt.com " target="_blank" rel="noopener noreferrer") WikipediaLa enciclopedia libre (15 oct 2024) Cultura organizacional 

           

            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://youtu.be/MV2gklOkZ5g?si=tHjTiXp2F0G2aRa7" target="_blank" rel="noopener noreferrer") Melvin Gesell (2016, 21 de noviembre) Estructura y Estrategia en la Organización ( 1 ) [Video]. Youtube. 

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
export default {
  name: 'Tema2',
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
