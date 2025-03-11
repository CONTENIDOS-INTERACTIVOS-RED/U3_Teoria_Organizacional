<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'4. Componentes de la cultura organizacional'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .bg-color-3.mb-5(data-aos="fade-up")
      .row.justify-content-center.align-items-center
        .col-lg-auto.mb-3.mb-lg-0
          figure
            img(src='@/assets/curso/tema4/1.png', alt='')
        .col-lg
          .p-4
            p.mb-0(data-aos="fade-up") La cultura organizacional es un conjunto de significados compartidos por los integrantes de una empresa, los cuales la diferencian de otras. Se compone de principios, creencias y conocimientos claves que son comunes entre sus miembros, definiendo así su comportamiento habitual (Luna González, 2015).
    
    p.mb-4 Componentes:

    .row.align-items-start.mb-5
      .col-lg-4.mb-3.mb-lg-0.order-1.order-lg-2
        figure
          img(src="@/assets/curso/tema4/2.png", alt="").mb-4.mb-lg-0
      .col-lg-8.order-2.order-lg-1
    
        AcordionA(tipo="b")
          .div(titulo="Valores organizacionales")
            p.mb-0 Son los principios fundamentales que guían el comportamiento y la toma de decisiones dentro de la organización. Representan lo que la empresa considera importante y pueden incluir valores como la innovación, la integridad, la responsabilidad social y el trabajo en equipo. Los valores organizacionales ayudan a establecer una identidad compartida entre los empleados y fomentan un sentido de pertenencia.
    
          .div(titulo="Creencias y suposiciones")
            p.mb-0 Son ideas y percepciones que los miembros de la organización tienen sobre su entorno, su trabajo y la manera en que deben comportarse. Estas creencias pueden ser explícitas o implícitas y, a menudo, influyen en la forma en que las personas interpretan la realidad y responden a los desafíos organizacionales.
    
          .div(titulo="Normas y reglas")
            p Incluyen políticas internas, procedimientos y estándares de comportamiento que regulan la forma en que los empleados deben actuar en diversas situaciones. Estas normas pueden ser formales, como códigos de conducta y reglamentos internos, o informales, como las expectativas implícitas sobre el trato entre compañeros o la vestimenta en el trabajo.
          .div(titulo="Símbolos y lenguaje")
            p Los símbolos organizacionales incluyen logotipos, colores corporativos, lemas y otros elementos visuales que representan la identidad de la empresa. El lenguaje organizacional se refiere a la terminología específica utilizada dentro de la empresa, como acrónimos, frases distintivas o expresiones comunes en la comunicación interna.
    
    .row.align-items-start.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema4/3.png", alt="").mb-4.mb-lg-0
      .col-lg-8
    
        AcordionA(tipo="b")
          .div(titulo="Historias y mitos")
            p.mb-0 Las historias organizacionales son relatos sobre eventos pasados que reflejan los valores y creencias de la empresa. Estas narrativas pueden incluir casos de éxito, anécdotas de los fundadores o episodios que destacan la cultura de la organización. Los mitos, por otro lado, son historias simbólicas que refuerzan la identidad organizacional y ayudan a construir una cultura cohesionada.
    
          .div(titulo="Liderazgo y estilo de dirección")
            p.mb-0 El papel de los líderes es fundamental en la construcción y mantenimiento de la cultura organizacional. Su comportamiento, estilo de liderazgo y valores influyen en la manera en que los empleados se relacionan con la empresa. Un liderazgo alineado con la cultura organizacional fomenta un ambiente de trabajo positivo y una mayor cohesión interna.
    
          .div(titulo="Estructura organizacional")
            p Hace referencia a la jerarquía, los roles y la distribución de responsabilidades dentro de la empresa. Una estructura organizacional flexible puede fomentar la innovación y el trabajo en equipo, mientras que una estructura rígida puede promover estabilidad y control.
          .div(titulo="Clima organizacional")
            p Se relaciona con la percepción que los empleados tienen sobre el ambiente de trabajo, incluyendo aspectos como la satisfacción laboral, la motivación, la comunicación interna y la relación entre compañeros. Un clima organizacional positivo fortalece la cultura organizacional y mejora el desempeño de los trabajadores.
          .div(titulo="Adaptabilidad y flexibilidad")
            p Es la capacidad de la organización para responder a cambios internos y externos sin comprometer su identidad. Una cultura organizacional flexible permite a la empresa evolucionar y ajustarse a nuevas tendencias del mercado, necesidades de los clientes y cambios tecnológicos.
          
    p.mb-4 La cultura organizacional se compone de valores fundamentales compartidos por la mayoría de los miembros de una empresa, lo que conforma una cultura dominante. Si esta no estuviera presente, la cultura organizacional perdería su impacto como variable independiente, porque no existiría una percepción común sobre qué comportamientos son adecuados o inadecuados.

    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0.order-1.order-lg-2
        figure
          img(src="@/assets/curso/tema4/4.png", data-aos="zoom-in")
      .col-lg-8.order-2.order-lg-1
        .bg-color-2.p-4.mb-3(data-aos="fade-left")
          p.mb-0 Contar con una cultura dominante fortalece el sentido de pertenencia de los empleados hacia un propósito que va más allá de sus intereses individuales, beneficiando a toda la organización. Además, contribuye a generar estabilidad en el entorno laboral, promoviendo un ambiente en el que los trabajadores se sientan cómodos, incrementen su productividad y sean reconocidos por sus contribuciones y su aprovechamiento del conocimiento organizacional.
        p(data-aos="fade-left") Para compartir y generar conocimiento de manera efectiva, es fundamental establecer mecanismos de control internos que filtren la información relevante para la organización, evitando que se pierda el sentido de colaboración y cohesión entre sus integrantes.
    
    .bg-full-width.bg-color-10.mb-5
      .px-4.px-md-5.py-4
        .row.align-items-center
          .col-lg-auto
            img(src="@/assets/curso/tema4/5.svg", style="max-width: 90px").mx-auto
          .col-lg
            p.mb-0.text-white En la medida en que una empresa logra afrontar con éxito la complejidad del entorno, se incrementan sus posibilidades de alcanzar sus objetivos. Esta dinámica da lugar al concepto de cultura organizacional o empresarial, el cual también permite evaluar la capacidad de los líderes para gestionar el cambio en las relaciones humanas y orientarlas hacia un beneficio común.

    #t_4_1.titulo-segundo(data-aos="flip-up")
      h2 #[span 4.1] Funciones de la cultura organizacional
    
    .bg-full-width.bg-h85-5
      .px-4.px-md-5
        .row.justify-content-around.align-items-center
          .col-lg-5
            figure
              img(src="@/assets/curso/tema4/6.svg", data-aos="zoom-in")
          .col-lg-6
            p(data-aos="fade-left").mb-4 Para estudiar la temática, lo invitamos a escuchar el siguiente podcast.
    
            TarjetaAudio.color-acento-botones.bg-color-white.mb-3(
              texto="Fundamentos de la innovación estratégica"
              tiempo
              :audio="require('../../assets/curso/podcast/podcast1.mp3')"
            )
    .bg-full-width.bg-color-12
      .px-4.px-md-5.py-4
        p.mb-0 Se estudia la cultura organizacional como un elemento clave que define la identidad, valores y normas dentro de una empresa, influyendo en el comportamiento de sus miembros. A través de 



    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://bdigital.uncu.edu.ar/fichas.php?idobjeto=15672 " target="_blank" rel="noopener noreferrer") Bertona, M. A. del R. (2020). Cultura organizacional y gestión intercultural: Análisis de casos. Biblioteca Digital de Uncuyo. 

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://es.wikipedia.org/wiki/Cultura_organizacional?utm_source=chatgpt.com" target="_blank" rel="noopener noreferrer") WikipediaLa enciclopedia libre (15 oct 2024) Cultura organizacional 

          
            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://youtu.be/QKLjwCMyv3M?si=uAWhO9tnyghljaJg" target="_blank" rel="noopener noreferrer") Cultura52 (2023, 13 de junio) ¿Cómo se construye cultura organizacional? . [Video] Youtube 

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
export default {
  name: 'Tema4',
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
