<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'5. Modelos de cultura organizacional'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .bg-full-width.bg-h85-6
      .p-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-12
            .row.justify-content-center.align-items-center
              .col-lg-8(data-aos="fade-left").order-2
                p.mb-0 La cultura organizacional es un elemento clave en la identidad y funcionamiento de una empresa, influyendo en su estructura, valores, estrategias y desempeño. Existen diversos modelos que permiten comprender cómo se configura y se desarrolla la cultura dentro de una organización. A continuación, se describen los principales modelos de cultura organizacional
              .col-lg-4(data-aos="zoom-in").order-1.mb-3.mb-lg-0
                img.img-fluid(src='@/assets/curso/tema5/1.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0

    #t_5_1.titulo-segundo(data-aos="flip-up")
      h2 #[span 5.1] Modelo de valores en competencia – Cameron y Quinn (1999)
    
    p.mb-4 Este modelo clasifica la cultura organizacional en cuatro tipos, según dos dimensiones: el grado de flexibilidad o estabilidad y la orientación interna o externa de la empresa.

    .row.justify-content-center.align-items-stretch.mb-3
      .col-lg-6.mb-3.mb-lg-0
        div.bg-h85-7(data-aos="fade-left")
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema5/2.svg").mx-auto
            .col-lg.text-white
              h5 Cultura clan
              p.mb-0 Se basa en la colaboración, la cercanía y el trabajo en equipo. 
              p.mb-0 Es común en organizaciones con una fuerte identidad corporativa y orientación hacia el bienestar de los empleados.

      .col-lg-6.mb-3.mb-lg-0
        div.bg-h85-7(data-aos="fade-left")
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema5/3.svg").mx-auto
            .col-lg.text-white
              h5 Cultura adhocrática
              p.mb-0 Se enfoca en la innovación y la creatividad. Las empresas con esta cultura promueven la autonomía y la experimentación, adaptándose rápidamente a los cambios del entorno.
    
    .row.justify-content-center.align-items-stretch.mb-5
      .col-lg-6.mb-3.mb-lg-0
        div.bg-h85-7(data-aos="fade-left")
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema5/4.svg").mx-auto
            .col-lg.text-white
              h5 Cultura de mercado
              p.mb-0 Priorizan la competitividad y los resultados. Las organizaciones con esta cultura están orientadas a los clientes, el rendimiento y la eficiencia

      .col-lg-6.mb-3.mb-lg-0
        div.bg-h85-7(data-aos="fade-left")
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema5/5.svg").mx-auto
            .col-lg.text-white
              h5 Cultura jerárquica
              p.mb-0 Se fundamenta en la estabilidad, el control y la estructura organizativa. Las reglas, procedimientos y cadenas de mando son elementos clave en este tipo de cultura.

    #t_5_2.titulo-segundo(data-aos="flip-up")
      h2 #[span 5.2] Modelo de Edgar Schein (1985) – Niveles de la cultura organizacional
    
    p.mb-4 Schein plantea que la cultura organizacional tiene tres niveles interconectados:

    
    div.bg-color-9.p-5.mb-5
      .row.justify-content-center.align-items-center.mb-5
        .col-lg-8
          figure
            img(src="@/assets/curso/tema5/6.svg", data-aos="zoom-in")


    #t_5_3.titulo-segundo(data-aos="flip-up")
      h2 #[span 5.3] Modelo de tipologías culturales de <em>Deal y Kennedy</em> (1982)
    
    p.mb-4 Este modelo clasifica la cultura organizacional en cuatro tipos, dependiendo del nivel de riesgo y la velocidad de retroalimentación en la toma de decisiones:

    TabsC.color-acento-contenido.mb-5
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Cultura de trabajo duro y diversión" :icon="require('@/assets/bullets/2.svg')")
        .row.justify-content-center
          .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
            h4 Cultura de trabajo duro y diversión
            p Propia de empresas con ritmo acelerado, donde la energía y la dedicación son esenciales, como en el sector de ventas.
    
          .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema5/7.png', alt='')
    
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Cultura de machos duros" :icon="require('@/assets/bullets/2.svg')")
        .row.justify-content-center
          .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
            h4 Cultura de machos duros
            p Se basa en la alta competitividad y toma de riesgos, común en industrias como la publicidad, el periodismo o el entretenimiento.
    
          .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema5/8.png', alt='')
    
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Cultura de procesos" :icon="require('@/assets/bullets/2.svg')")
        .row.justify-content-center
          .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
            h4 Cultura de procesos
            p Predomina en organizaciones burocráticas donde se prioriza el cumplimiento de normas y procedimientos, como en instituciones gubernamentales.
    
          .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema5/9.png', alt='', style="width: 100%;")
    
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Cultura <em>Bet-the-Company</em> (Apostar la empresa)" :icon="require('@/assets/bullets/2.svg')")
        .row.justify-content-center
          .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
            h4 Cultura <em>Bet-the-Company</em> (Apostar la empresa)
            p Se encuentra en empresas donde las decisiones estratégicas a largo plazo son fundamentales, como en la industria petrolera o aeroespacial.
    
          .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema5/10.png', alt='', style="width: 100%;")
    

    #t_5_4.titulo-segundo(data-aos="flip-up")
      h2 #[span 5.4] Modelo de Hofstede (1991) – Dimensiones culturales
    
    p.mb-5 Este modelo estudia la cultura organizacional a través de dimensiones que reflejan diferencias en valores y comportamiento en distintos países y empresas:

    .bg-full-width.bg-fondo-5
      .px-4.px-md-5.pb-md-3
        .row.justify-content-center.mb-5
          .col-lg-8.mb-3.mb-lg-0
            p(data-aos="fade-left") Un #[em briefing] efectivo es esencial para guiar proyectos creativos de manera clara y alineada con los objetivos.
    
            SlyderF(columnas="col-12 col-lg-6")
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema5/11.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Distancia del poder
                p.text-center Grado en que se aceptan desigualdades jerárquicas dentro de la organización.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema5/12.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Individualismo vs. colectivismo
                p.text-center Preferencia por el éxito individual o el trabajo en equipo.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema5/13.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Masculinidad vs. feminidad
                p.text-center Enfoque en la competencia y logros (masculino) o en la cooperación y el bienestar (femenino).
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema5/14.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Evasión de la incertidumbre
                p.text-center Nivel de tolerancia a la ambigüedad y el cambio.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema5/15.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Orientación a largo plazo vs. corto plazo
                p.text-center Priorización de la planificación estratégica o de resultados inmediatos.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema5/16.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Indulgencia vs. restricción
                p.text-center Grado en que se permite la expresión de emociones y la satisfacción de necesidades personales.
    
          .col-lg-4
            figure
              img(src='@/assets/curso/tema5/17.png', alt='')
      
    #t_5_5.titulo-segundo(data-aos="flip-up")
      h2 #[span 5.5] Modelo de <em>Schneider</em> (1994) – Cultura organizacional basada en valores
    
    p.mb-4 Schneider propone que las empresas pueden tener diferentes enfoques culturales, según sus valores y objetivos principales:

    
    div.bg-color-9.p-5.mb-5
      .row.justify-content-center.align-items-center.mb-5
        .col-lg-8
          figure
            img(src="@/assets/curso/tema5/18.svg", data-aos="zoom-in")



    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.redalyc.org/articulo.oa?id=425951181004 " target="_blank" rel="noopener noreferrer") García Navarro, V. A. (2017). Desarrollo de un modelo de diagnóstico de cultura organizacional. Perspectivas, 20(39), 1-29 
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://es.wikipedia.org/wiki/Cultura_organizacional?utm_source=chatgpt.com " target="_blank" rel="noopener noreferrer") WikipediaLa enciclopedia libre (15 oct 2024) Cultura organizacional  
            

            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://youtu.be/OmGPHO5RzSs?si=RW5G2pzOBTpCikUg " target="_blank" rel="noopener noreferrer") Cultura52 (2023, 13 de junio) ¿Cómo se construye cultura organizacional? . [Video] Youtube 

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')
  
</template>

<script>
export default {
  name: 'Tema5',
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
