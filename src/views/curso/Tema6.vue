<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'6. Teorías del cambio organizacional'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .bg-full-width.bg-color-4
      .px-4.px-md-5.py-4
        p.mb-0 Las teorías del cambio organizacional explican cómo y por qué las organizaciones cambian con el tiempo, qué factores impulsan esos cambios y qué estrategias pueden utilizarse para gestionarlos de manera efectiva. Estas teorías ayudan a comprender la evolución de las empresas y a diseñar intervenciones para mejorar su desempeño.
    
    .bg-full-width.bg-color-5.mb-lg-5
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-8.order-2
            h2.mb-4(data-aos="flip-up") Teorías del cambio organizacional
            p.mb-4(data-aos="fade-right") En el PDF <b>Teorías del cambio organizacional</b>, se presentan los principales enfoques teóricos que explican cómo las organizaciones pueden gestionar el cambio de manera estructurada y efectiva. Se analizan modelos como la Teoría del Cambio de Kurt Lewin, el Desarrollo Organizacional (DO), la teoría de la complejidad y el cambio emergente, así como el Modelo de Kotter, destacando sus beneficios, aplicaciones y desafíos en el ámbito empresarial. A través de este material, se proporciona una guía para comprender las dinámicas del cambio y su impacto en la gestión organizacional, facilitando estrategias para su implementación exitosa.
    
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_1.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Teorías del cambio organizacional.
    
          .col-lg-4.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema6/1.png', alt='')
 
    .bg-full-width.border-top.actividad.bg-color-actividad
      .p-4.p-md-5
        #Actividad                
          <Actividad :cuestionario="cuestionario"/>

    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.redalyc.org/articulo.oa?id=65821209  " target="_blank" rel="noopener noreferrer") Pérez de Maldonado, I., Maldonado Pérez, M., & Bustamante Uzcátegui, S. (2006). Clima organizacional y gerencial: Inductores del cambio organizacional. Investigación y Postgrado, 21(2). 
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.uv.es/garzon/psicologia%20politica/N5-5.pdf" target="_blank" rel="noopener noreferrer") Rodríguez, A. (s.f.). Poder y políticas en las organizaciones. Universidad de Granada. 

           

            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://youtu.be/EinotCVXKHo?si=UhAZQYhoQlH4Lsvt " target="_blank" rel="noopener noreferrer") IES Valle de Uco (2016, 21 de marzo) ANÁLISIS y DESARROLLO ORGANIZACIONAL. [Video] Youtube 

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')
  
</template>

<script>
import Actividad from '@/components/actividad/Actividad.vue'
export default {
  name: 'Tema6',
  components: {
    Actividad,
  },
  data() {
    return {
      cuestionario: {
        tema: 'Herramientas colaborativas para la construcción de paz',
        titulo: 'Ponte a prueba',
        introduccion:
          'Demuestra lo que aprendiste en esta unidad y pon a prueba tus conocimientos.',
        barajarPreguntas: true,
        preguntas: [
          {
            id: 1,
            texto:
              '¿Cuál es una característica principal de la estructura organizacional funcional?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Se basa en la especialización por áreas de trabajo. ',
                esCorrecta: true,
              },
              {
                id: 'b',
                texto:
                  'Promueve equipos multidisciplinarios sin jerarquías definidas.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto:
                  'Opera con proyectos temporales sin departamentos fijos.',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto:
                  'Limita la división del trabajo en los equipos internos.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto:
              '¡Correcto! La estructura funcional organiza el trabajo por áreas especializadas, lo que mejora la eficiencia y permite un mayor desarrollo del conocimiento en cada función.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 2,
            texto: '¿Qué define a la estructura organizacional matricial?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto:
                  'La combinación de jerarquía funcional y gestión por proyectos. ',
                esCorrecta: true,
              },
              {
                id: 'b',
                texto:
                  'La centralización total de decisiones en la alta dirección.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto: 'La autonomía total de los empleados sin supervisión.',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'La segmentación de procesos sin coordinación interna.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto:
              '¡Muy bien! La estructura matricial equilibra funciones y proyectos, promoviendo colaboración y flexibilidad para mejorar la eficiencia y adaptabilidad organizacional.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 3,
            texto:
              '¿Cuál es el propósito de la cultura organizacional dentro de una empresa?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto:
                  'Guiar valores, creencias y comportamientos compartidos. ',
                esCorrecta: true,
              },
              {
                id: 'b',
                texto:
                  'Estandarizar procedimientos sin considerar el factor humano.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto:
                  'Mantener estructuras rígidas sin posibilidad de innovación.',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto:
                  'Implementar normas sin enfoque en la identidad corporativa.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto:
              '¡Estupendo! La cultura organizacional define valores y creencias, fortaleciendo la identidad corporativa y el sentido de pertenencia entre los colaboradores.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 4,
            texto:
              '¿Cómo influye la cultura organizacional en el desempeño de los empleados?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto:
                  'Fomenta compromiso, motivación y sentido de pertenencia. ',
                esCorrecta: true,
              },
              {
                id: 'b',
                texto: 'Reduce la comunicación y el trabajo en equipo interno.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto:
                  'Restringe la toma de decisiones y creatividad individual.',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto:
                  'Genera un ambiente de trabajo sin identidad corporativa.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto:
              '¡Correcto! Una cultura organizacional sólida impulsa el compromiso y la motivación, creando un entorno favorable para el desempeño y la innovación.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 5,
            texto:
              '¿Qué caracteriza a una estructura organizacional descentralizada?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto:
                  'La toma de decisiones en diferentes niveles organizacionales',
                esCorrecta: true,
              },
              {
                id: 'b',
                texto: 'La concentración de autoridad en una sola persona.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto:
                  'La ejecución de tareas sin asignación de responsabilidades.',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'La eliminación de comunicación entre departamentos.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto:
              '¡Excelente! La descentralización distribuye la toma de decisiones, agilizando procesos y permitiendo una mayor autonomía en distintos niveles de la organización.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
        ],
        mensaje_final_aprobado:
          '¡Felicidades! Has superado la prueba con éxito.',
        mensaje_final_reprobado:
          'Te recomendamos repasar nuevamente la unidad para reforzar los conceptos clave antes de volver a intentarlo.',
      },
    }
  },
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass">
.bg-color-actividad
  background-color: #EBF1F5
</style>
