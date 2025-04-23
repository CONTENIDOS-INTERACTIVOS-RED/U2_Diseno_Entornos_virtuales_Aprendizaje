<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'1. Plataformas tecnológicas para la gestión del aprendizaje'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .bg-color-3.mb-5(data-aos="fade-up")
      .row.justify-content-center.align-items-center
        .col-lg.order-lg-2
          .p-4
            p.mb-0(data-aos="fade-up") El avance de las tecnologías digitales ha impulsado transformaciones profundas en los procesos educativos, dando lugar a entornos virtuales que amplían las posibilidades de acceso, personalización y seguimiento del aprendizaje. En este contexto, las plataformas tecnológicas para la gestión del aprendizaje, comúnmente conocidas como LMS (Learning Management Systems), se han consolidado como herramientas esenciales para estructurar experiencias educativas #[b flexibles, dinámicas y centradas en el estudiante.]    
        .col-lg-auto.mb-3.mb-lg-0.order-lg-1
          figure
            img.img-a.img-t(src='@/assets/curso/temas/3.png', alt='') 

    .row.mb-5       
      .col-lg-8
        p(data-aos="fade-down") Estas plataformas permiten #[b planificar, distribuir contenidos, evaluar el aprendizaje y facilitar la comunicación] entre docentes y estudiantes. Su adecuada implementación no solo organiza y mejora la eficacia del proceso formativo, sino que también #[b fomenta la participación activa y colaborativa.] Ejemplos como Moodle, Canvas y Google Classroom, se han convertido en referentes por su adaptabilidad, enfoque pedagógico y accesibilidad.              

        .bg-color-4.p-4.mb-4(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img.img-a.img-t(src="@/assets/curso/temas/4.svg")
            .col-lg
              p.mb-0 Desde una perspectiva pedagógica, el uso estratégico de estas tecnologías, permite al docente concebir entornos donde el estudiante interactúa con contenidos relevantes, participa en actividades integradas y recibe feedback oportuno. Asimismo, #[b promueve el desarrollo de habilidades digitales] en docentes y amplía la cobertura educativa, sin comprometer la calidad. 
        h3(data-aos="fade-down") Fundamentos y características de los LMS 
        p(data-aos="fade-down") Los Learning Management Systems (LMS), o Sistemas de Gestión del Aprendizaje, son piezas claves en el diseño y ejecución de propuestas educativas en los entornos virtuales. Su propósito principal es #[b facilitar la distribución de contenidos, la gestión de usuarios y el desarrollo de actividades de evaluación y comunicación] desde un espacio digital centralizado (Silva Quiroz, 2011). Un LMS integra funcionalidades como:                
      .col-lg-4.mb-3.mb-lg-0 
        figure
          img.img-a.img-t(src="@/assets/curso/temas/5.png", data-aos="zoom-in") 


    .row.justify-content-center.mb-5           
      .col-lg-3.mb-3.mb-lg-0
        .bg-color-2.h-100.p-3
          h5(data-aos="fade-down") 01                           
          p.mb-0.text-center(data-aos="fade-up") Organización de cursos y rutas de aprendizaje.
      .col-lg-3.mb-3.mb-lg-0
        .bg-color-2.h-100.p-3
          h5(data-aos="fade-down") 02                           
          p.mb-0.text-center(data-aos="fade-up") Carga y visualización de materiales didácticos.
      .col-lg-3.mb-3.mb-lg-0
        .bg-color-2.h-100.p-3
          h5(data-aos="fade-down") 03                          
          p.mb-0.text-center(data-aos="fade-up") Monitoreo del progreso del estudiante.
      .col-lg-3.mb-3.mb-lg-0
        .bg-color-2.h-100.p-3
          h5(data-aos="fade-down") 04                          
          p.mb-0.text-center(data-aos="fade-up") Interacción mediante foros, mensajería interna y videoconferencias.                       


    .row.align-items-center.mb-5 
      .col-lg-3.mb-3.mb-lg-0 
        figure
          img.img-a.img-t(src="@/assets/curso/temas/6.png", data-aos="zoom-in")           
      .col-lg-9
        .bg-color-1.p-4.mb-4(data-aos="fade-left")
          p.mb-0 Estas funciones promueven una experiencia educativa más flexible, personalizada y continua. Desde el enfoque del diseño instruccional, el uso de un LMS debe contemplar aspectos como la segmentación de contenidos, el diseño de rutas adaptativas de aprendizaje y la evaluación continua. Por ejemplo, en la formación docente, estas plataformas pueden integrar recursos multimedia, actividades prácticas y foros de reflexión que favorecen la construcción colectiva del conocimiento y el desarrollo de habilidades blandas como la comunicación, el pensamiento crítico y la autorregulación. 

        p(data-aos="fade-down") Un LMS efectivo, se fundamenta en #[b principios técnicos y pedagógicos claves], que se resumen a continuación:               

    .bg-full-width-1.bg-fondo-1(data-aos="fade-right")
      .px-4.px-md-5.pb-md-3
        .row.justify-content-center       
          .col-lg-8
            SlyderF.text-center(columnas="col-12 col-lg-6")
              .bg-color-white.p-4.h-100.sha.brounded-sm
                img(src='@/assets/curso/temas/8.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.mb-4 Accesibilidad  
                p Garantiza que todos los usuarios, incluidos aquellos con discapacidades, puedan interactuar con la plataforma.

              .bg-color-white.p-4.h-100.sha.brounded-sm
                img(src='@/assets/curso/temas/8.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.mb-4 Interoperabilidad 
                p Permite que el LMS se integre con otros sistemas tecnológicos y estándares educativos.

              .bg-color-white.p-4.h-100.sha.brounded-sm
                img(src='@/assets/curso/temas/8.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.mb-4 Escalabilidad 
                p Facilita su uso en proyectos pequeños o grandes, sin comprometer el rendimiento o la calidad del servicio.

              .bg-color-white.p-4.h-100.sha.brounded-sm
                img(src='@/assets/curso/temas/8.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.mb-4 Usabilidad 
                p Asegura una interfaz intuitiva y amigable, lo que mejora la experiencia de usuario y la participación activa.

              .bg-color-white.p-4.h-100.sha.brounded-sm
                img(src='@/assets/curso/temas/8.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.mb-4 Alineación pedagógica  
                p Vincula las funcionalidades del sistema con los modelos y objetivos educativos específicos (Bautista Pérez, Borges Sáiz & Forés Miravalles, 2016).

          .col-lg-4
            figure
              img.img-a.img-t(src='@/assets/curso/temas/7.png', alt='')                  

    .bg-full-width.bg-color-5.text-white.mb-5(data-aos="fade-up")
      .px-4.px-md-5.py-4
        .row.align-items-center
          .col-lg-auto
            img.img-a.img-t(src="@/assets/curso/temas/13.svg")
          .col-lg
            p.mb-0 En definitiva, un LMS bien implementado no solo facilita la gestión educativa, sino que también enriquece las dinámicas pedagógicas mediante el uso estratégico de sus herramientas. Esto requiere una visión crítica y contextualizada que permita seleccionar la plataforma más adecuada, según el entorno, los objetivos de aprendizaje y el perfil de los estudiantes.

    h3(data-aos="fade-down") Comparativo de plataformas: Moodle, Canvas y Google Classroom
    p(data-aos="fade-down") Seleccionar una plataforma adecuada para la gestión del aprendizaje, es una decisión #[b estratégica] en todo proyecto educativo. Moodle, Canvas y Google Classroom se destacan como los entornos virtuales más utilizados a nivel global, cada uno con características específicas que responden a distintas #[b necesidades institucionales, pedagógicas y tecnológicas.]      

    .bg-full-width-2.bg-fondo-2
      .px-4.px-md-5.pb-md-3
        TabsC(data-aos="fade-right").color-primario.mb-5
          .bg-color-6.border.px-4.p-md-5.py-3(titulo="Moodle" :icon="require('@/assets/bullets/icon.svg')")
            .row.justify-content-center
              .col-lg-7.col-xl-8.mb-4.mb-md-0
                h4 Moodle 
                p Plataforma de código abierto, altamente personalizable, ideal para instituciones que requieren autonomía tecnológica y estructuras curriculares complejas.
        
              .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
                figure(data-aos="zoom-in")
                  img.img-a.img-t(src='@/assets/curso/temas/14.png', alt='')    

          .bg-color-6.border.px-4.p-md-5.py-3(titulo="Canvas" :icon="require('@/assets/bullets/icon.svg')")
            .row.justify-content-center
              .col-lg-7.col-xl-8.mb-4.mb-md-0
                h4 Canvas 
                p Ofrece una interfaz intuitiva y flexible, con énfasis en la experiencia del usuario y en la integración de herramientas externas, lo cual facilita su implementación.
        
              .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
                figure(data-aos="zoom-in")
                  img.img-a.img-t(src='@/assets/curso/temas/15.png', alt='')  

          .bg-color-6.border.px-4.p-md-5.py-3(titulo="Google Classroom" :icon="require('@/assets/bullets/icon.svg')")
            .row.justify-content-center
              .col-lg-7.col-xl-8.mb-4.mb-md-0
                h4 Google Classroom 
                p Se caracteriza por su simplicidad y sincronización con el ecosistema de Google, siendo accesible para entornos con recursos tecnológicos limitados, especialmente en instituciones que ya utilizan Google Workspace.
        
              .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
                figure(data-aos="zoom-in")
                  img.img-a.img-t(src='@/assets/curso/temas/16.png', alt='') 

        p(data-aos="fade-left") Estas plataformas ofrecen distintas ventajas en cuanto a administración de contenidos, interacción docente-estudiante, herramientas de evaluación y accesibilidad desde dispositivos móviles. En programas de formación docente, por ejemplo:


        div.row.justify-content-center.align-items-stretch.text-center
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100.br-1
              img.mx-auto.d-block.mb-4(src="@/assets/curso/temas/17.svg" alt="" style="width: 90px")
              h5 Moodle
              p.mb-0 Permite estructurar contenidos progresivos y evaluaciones personalizadas. 

          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100.br-1
              img.mx-auto.d-block.mb-4(src="@/assets/curso/temas/18.svg" alt="" style="width: 90px")
              h5 Canvas 
              p.mb-0 Favorece experiencias de aprendizaje visualmente atractivas y con fuerte soporte analítico.

          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100.br-1
              img.mx-auto.d-block.mb-4(src="@/assets/curso/temas/19.svg" alt="" style="width: 90px")
              h5 Google Classroom 
              p.mb-0 Facilita la organización de actividades colaborativas de manera simple y directa.

    .bg-full-width.bg-h86.mb-5
      .px-4.px-md-5
        .row.justify-content-center.align-items-center
          .col-lg-12
            .row.justify-content-center.align-items-center
              .col-lg-4.mb-3.mb-lg-0(data-aos="zoom-in")
                img.img-a.img-t(src='@/assets/curso/temas/20.svg', alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0                
              .col-lg-8(data-aos="fade-left")
                p.mb-0.mt-5 La elección de una u otra plataforma, debe estar sustentada en un #[b diagnóstico institucional, considerando las competencias tecnopedagógicas del cuerpo docente] y las #[b necesidades específicas del estudiantado]. Desarrollar criterios para seleccionar, adaptar e integrar estos sistemas de forma estratégica, fortalece la capacidad de diseñar entornos de aprendizaje #[b inclusivos, eficientes y sostenibles]. 

    .titulo-figura(data-aos="fade-right")
      h5 Tabla 1. 
      span Tabla comparativa Moodle, Canvas y Google Classroom

    .tabla-a-1.mb-5(data-aos="fade-left") 
      table
        thead.text-center
          tr
            th Criterio
            th Moodle
            th Canvas
            th Google Classroom
        tbody
          tr
            td.text-bold Tipo de plataforma
            td Código abierto.
            td Licencia comercial (con opción gratuita para educación).                            
            td Gratuita con cuenta Google Workspace.

          tr
            td.text-bold Instalación y alojamiento
            td Necesita servidor propio (autoalojado).
            td Basada en la nube (SaaS).                            
            td Basada en la nube. 

          tr
            td.text-bold Interfaz de usuario 
            td Completa, pero menos intuitiva.
            td Intuitiva y moderna.                            
            td Simple y amigable.

          tr
            td.text-bold Integración con herramientas
            td Alta (#[i plugins], LTI, SCORM, H5P, BigBlueButton, etc.).
            td Alta (LTI, multimedia, herramientas externas).                            
            td Limitada a herramientas de Google.

          tr
            td.text-bold Evaluación y seguimiento
            td Avanzado: rúbricas, cuestionarios, seguimiento por estudiante.
            td Avanzado: rúbricas, analítica, reportes automáticos.                            
            td Básico: tareas, calificaciones y comentarios. 

          tr
            td.text-bold Accesibilidad y usabilidad
            td Alta personalización con posibilidad de ajustes de accesibilidad.
            td Compatible con estándares de accesibilidad (WCAG).                            
            td Interfaz clara, pero limitada en accesibilidad avanzada.

          tr
            td.text-bold Comunicación
            td Foros, mensajería interna, videoconferencia integrada.
            td Mensajes, foros, comentarios en tareas, videoconferencias externas.                            
            td Comentarios en tareas y publicaciones tipo muro.

          tr
            td.text-bold Ideal para
            td Instituciones que requieren control, personalización y alta escalabilidad.
            td Universidades con enfoque en experiencia del usuario y analítica educativa.                            
            td Escuelas que ya usan Google Workspace y buscan implementación rápida.                                                               
    .bg-full-width.bg-h87.mb-5
      .px-4.px-md-5
        .row.justify-content-center.align-items-center
          .col-lg-12
            .row.justify-content-center.align-items-center
              .col-lg-8.mb-3.mb-lg-0(data-aos="fade-left")
                h5.mt-5 Ejemplo práctico
                p.mb-5 Tres instituciones educativas de diversos tipos, enfrentan el reto de implementar un entorno virtual de aprendizaje para acompañar procesos de formación con enfoque en habilidades blandas como la comunicación, el liderazgo, la colaboración y la autonomía. Se solicita identificar cuál de las plataformas: Moodle, Canvas o Google Classroom, se adapta mejor a cada contexto para lograr una implementación pedagógica efectiva.
              .col-lg-4(data-aos="zoom-in")
                img.img-a.img-t(src='@/assets/curso/temas/21.svg', alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0 

    .row.align-items-start.mb-5
      .col-lg-4
        figure(data-aos="zoom-in")
          img.img-a.img-t(src="@/assets/curso/temas/22.png", alt="")
      .col-lg-8
        AcordionA(tipo="b")(data-aos="fade-left")
          .div(titulo="Institución A: Universidad pública con enfoque en investigación")
            ul.lista-ul--color
              li.mb-3.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 #[b Recursos disponibles:] equipo de desarrollo TIC propio, docentes con alto nivel de formación digital, interés en adaptar contenidos a múltiples niveles de profundidad.
              li.mb-3.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 #[b Necesidades:] crear rutas de aprendizaje personalizadas, usar herramientas de evaluación avanzada, fomentar la reflexión crítica y la autorregulación.
              li.mb-3.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 #[b Recomendación:] Moodle
              li.mb-3.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 #[b Justificación:] la flexibilidad de Moodle permite integrar actividades gamificadas, foros estructurados y seguimiento por competencias. Su arquitectura modular favorece el diseño instruccional complejo y el desarrollo de la autonomía del estudiante.  

          .div(titulo="Institución B: Universidad internacional con enfoque en experiencia del usuario")
            ul.lista-ul--color
              li.mb-3.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 #[b Recursos disponibles:] acceso a servicios en la nube, estudiantes internacionales, enfoque en movilidad y compatibilidad con herramientas externas.
              li.mb-3.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 #[b Necesidades:] facilitar navegación fluida, retroalimentación continua y trabajo colaborativo, entre diferentes culturas.
              li.mb-3.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 #[b Recomendación:] Canvas
              li.mb-3.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 #[b Justificación:] Canvas ofrece una interfaz amigable, integración sencilla con apps externas y analítica de aprendizaje que permite a docentes identificar barreras y oportunidades para mejorar habilidades como la comunicación intercultural y el pensamiento crítico. 

          .div(titulo="Institución C: Centro educativo técnico en zona rural, con conectividad limitada")
            ul.lista-ul--color
              li.mb-3.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 #[b Recursos disponibles:] dispositivos con Google Workspace, acceso limitado a Internet, docentes en proceso de formación digital.
              li.mb-3.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 #[b Necesidades:] plataforma intuitiva, uso sin instalaciones locales, fomentar la participación y el trabajo en equipo básico.
              li.mb-3.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 #[b Recomendación:] Google Classroom
              li.mb-3.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 #[b Justificación:] por su simplicidad, compatibilidad con herramientas conocidas (Docs, Meet, Drive) y bajo consumo de datos, Classroom permite implementar rápidamente, actividades colaborativas, promover la responsabilidad y la empatía, a través de proyectos compartidos.

    .row.mb-5       
      .col-lg-8
        p(data-aos="fade-down") Este ejercicio evidencia que la elección de un LMS no debe centrarse en la popularidad de la herramienta, sino en la capacidad de responder pedagógicamente al contexto, facilitando el logro de competencias digitales y habilidades blandas claves para el siglo XXI, como la autorregulación, la colaboración y la resolución de problemas.           

        .bg-color-4.p-4.mb-4(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img.img-a.img-t(src="@/assets/curso/temas/23.svg")
            .col-lg
              p.mb-0 Integrar estas plataformas de forma estratégica en proyectos educativos, permite que el estudiante de posgrado no solo adquiera conocimientos técnicos, sino que refuerce su capacidad de análisis, liderazgo y toma de decisiones fundamentadas. Esto contribuye a su formación como profesional reflexivo, adaptable y comprometido con la calidad educativa en entornos digitales.               
      .col-lg-4.mb-3.mb-lg-0 
        figure
          img.img-a.img-t(src="@/assets/curso/temas/29.png", data-aos="zoom-in") 

    h3(data-aos="fade-down") Criterios para seleccionar e implementar un LMS
    p(data-aos="fade-down") A continuación, se resumen los aspectos claves que se deben considerar al momento de elegir una plataforma LMS, en función del contexto educativo.                                      
    .bg-full-width.bg-fondo-slider.mb-5(data-aos="fade-right")
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img.img-a.img-t(src="@/assets/curso/temas/24.png")          
            .col-lg-7
              h5 Pedagógicos 
              ul.lista-ul--color
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Compatible con metodologías activas.
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Soporte para evaluación, variada.
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Promueve habilidades blandas.
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Favorece el aprendizaje autónomo y personalizado.                

          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img.img-a.img-t(src="@/assets/curso/temas/25.png")          
            .col-lg-7
              h5 Tecnológicos 
              ul.lista-ul--color
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Interoperabilidad con otras herramientas.
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Escalabilidad para crecer con la institución.
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Acceso multiplataforma.
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Actualizaciones y soporte técnico.              

          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img.img-a.img-t(src="@/assets/curso/temas/26.png")          
            .col-lg-7
              h5 Institucionales  
              ul.lista-ul--color
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Costos de implementación y mantenimiento.
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Recursos disponibles (humanos y técnicos).
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Nivel de alfabetización digital.
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Alineación con políticas educativas.              

          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img.img-a.img-t(src="@/assets/curso/temas/27.png")          
            .col-lg-7
              h5 Accesibilidad e inclusión 
              ul.lista-ul--color
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Cumplimiento de estándares WCAG.
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Adaptabilidad a diversas necesidades.
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Interfaz amigable.
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Navegación intuitiva y clara.              

          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img.img-a.img-t(src="@/assets/curso/temas/28.png")          
            .col-lg-7
              h5 Comunicación y colaboración  
              ul.lista-ul--color
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Herramientas sincrónicas y asincrónicas.
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Foros, chats y videollamadas.
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Trabajo colaborativo.
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Seguimiento de participación.
    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.redalyc.org/pdf/368/36812036015.pdf" target="_blank" rel="noopener noreferrer") Sánchez Rodríguez, J. (2009). Plataformas de enseñanza virtual para entornos educativos. Pixel-Bit. Revista de Medios y Educación.  

            p.d-flex.my-4
              img.me-3(src='@/assets/template/book.svg' :style="{'max-width':'16px'}")
              a(href="https://dialnet.unirioja.es/descarga/articulo/8229710.pdf" target="_blank" rel="noopener noreferrer") Ramos Vite, M. M. del R., & Macahuachi Nuñez De Castillon, L. C. (2021). Plataformas virtuales como herramientas de enseñanza. Dominio de las Ciencias, 7(3), 1080–1098. Recuperado de 

            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=JasX1u-6M0s" target="_blank" rel="noopener noreferrer") cibernautas. (2023). open lms ¿CUÁL ES MEJOR?.

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({}),

  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
