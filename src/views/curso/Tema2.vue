<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'2. Creación de recursos educativos digitales'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0 
        figure
          img.img-a.img-t(src="@/assets/curso/temas/30.png", data-aos="zoom-in")             
      .col-lg-8
        .bg-color-1.p-4.mb-4(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img.img-a.img-t(src="@/assets/curso/temas/31.svg")
            .col-lg
              p.mb-0 En el contexto de la #[b transformación digital de la educación, la creación de recursos educativos digitales (RED)], se consolida como una estrategia fundamental para enriquecer los procesos de enseñanza y aprendizaje, en entornos virtuales. Estos recursos, cuando se diseñan con base en #[b principios pedagógicos sólidos], favorecen aspectos esenciales como la #[b motivación, la autonomía, la interacción y la accesibilidad], garantizando experiencias inclusivas y significativas.
        p(data-aos="fade-down") El diseño de RED va #[b más allá del simple uso de herramientas tecnológicas]. Implica una comprensión profunda de los #[b objetivos de aprendizaje, el perfil del estudiante y las competencias por desarrollar]. En contextos de especialización, este proceso requiere la implementación de #[b enfoques didácticos innovadores], que fomenten habilidades claves como el #[b pensamiento crítico, la autorregulación y la comunicación efectiva].

    .bg-full-width.bg-color-3(data-aos="fade-down")
      .px-4.px-md-5.py-4
        .row.align-items-center
          .col-lg
            p.mb-0 Entre los recursos más efectivos se encuentran las #[b infografías, videos interactivos, presentaciones animadas, simuladores y actividades gamificadas], los cuales dinamizan el contenido y facilitan la apropiación del conocimiento. A su vez, se destaca la importancia de utilizar #[b plataformas abiertas y herramientas digitales accesibles], que permitan la creación de materiales #[b reutilizables y adaptables], considerando la #[b diversidad de contextos y estilos de aprendizaje].           
          .col-lg-auto
            img.img-a.img-t(src="@/assets/curso/temas/32.svg")

    .bg-full-width.bg-color-7.mb-5(data-aos="fade-up")
      .px-4.px-md-5.py-4 
        p.mb-0 Además, se debe realizar una #[b evaluación constante] de los recursos creados, verificando su #[b pertinencia, claridad, interactividad y accesibilidad], y asegurando su alineación con los #[b objetivos curriculares] y el desarrollo de #[b competencias transversales]. 

    h3(data-aos="fade-down") Herramientas de autor para contenidos interactivos
    p(data-aos="fade-down") El diseño de contenidos digitales interactivos, se ha convertido en una #[b competencia esencial] para los educadores que trabajan en entornos virtuales. Las #[b herramientas de autor] como Genially, H5P y Articulate Storyline, ofrecen soluciones versátiles para construir experiencias de aprendizaje activas, significativas y personalizadas.     


    TabsC(data-aos="fade-right").color-primario.mb-5
      .bg-color-6.border.px-4.p-md-5.py-3(titulo="Genially" :icon="require('@/assets/bullets/icon1.svg')")
        .row.justify-content-center
          .col-md-8.col-lg-5.col-xl-4.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img.img-a.img-t(src='@/assets/curso/temas/33.png', alt='')              
          .col-lg-7.col-xl-8.mb-4.mb-md-0
            h4 Genially  
            p Fácil de usar y con enfoque visual atractivo. Permite crear #[b presentaciones, infografías animadas, mapas interactivos] y escape #[i rooms] educativos. Ideal para estrategias de gamificación y #[i storytelling]. 

      .bg-color-6.border.px-4.p-md-5.py-3(titulo="H5P" :icon="require('@/assets/bullets/icon1.svg')")
        .row.justify-content-center
          .col-md-8.col-lg-5.col-xl-4.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img.img-a.img-t(src='@/assets/curso/temas/34.png', alt='')            
          .col-lg-7.col-xl-8.mb-4.mb-md-0
            h4 H5P 
            p #[i Plugin] de #[b código abierto] con más de 40 tipos de actividades interactivas: #[b cuestionarios, líneas de tiempo, arrastrar y soltar], etc. Se integra con Moodle y WordPress. Favorece recursos #[b reutilizables y accesibles] (UNESCO, 2020).

      .bg-color-6.border.px-4.p-md-5.py-3(titulo="Articulate Storyline" :icon="require('@/assets/bullets/icon1.svg')")
        .row.justify-content-center
          .col-md-8.col-lg-5.col-xl-4.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img.img-a.img-t(src='@/assets/curso/temas/35.png', alt='')            
          .col-lg-7.col-xl-8.mb-4.mb-md-0
            h4 Articulate Storyline 
            p Herramienta robusta de diseño instruccional. Permite #[b navegación personalizada, simulaciones interactivas, grabaciones de voz y animaciones]. Requiere mayor curva de aprendizaje, pero ideal para #[b secuencias formativas complejas].


    .row.mb-5
      .col-lg-8.mb-3.mb-lg-0
        .bg-color-8.p-4(data-aos="fade-left")
          p.mb-0 Seleccionar la herramienta adecuada no debe basarse solo en sus capacidades técnicas, sino en su coherencia con el modelo pedagógico, el perfil de los estudiantes, la infraestructura disponible y los propósitos formativos. Por ejemplo:
        .bg-color-2.p-4(data-aos="fade-right")
          ul.lista-ul--color.mb-0
            li.mb-3.d-flex
              i.far.fa-arrow-alt-circle-right.color-1
              p.mb-0 En una capacitación docente sobre comunicación asertiva, Genially puede ser útil para simular escenarios con casos interactivos.
            li.mb-0.d-flex
              i.far.fa-arrow-alt-circle-right.color-1
              p.mb-0 En un módulo de evaluación por desempeño, H5P permite generar rúbricas interactivas integradas al entorno virtual.          
      .col-lg-4 
        figure
          img.img-a.img-t(src="@/assets/curso/temas/36.png", data-aos="zoom-in") 

    .bg-full-width.bg-color-5.text-white.mb-5(data-aos="fade-up")
      .px-4.px-md-5.py-4
        .row.align-items-center
          .col-lg-auto
            img.img-a.img-t(src="@/assets/curso/temas/37.svg")
          .col-lg
            p.mb-0 El uso estratégico de estas herramientas, facilita la integración de contenidos dinámicos que no solo mejoran la experiencia del usuario, sino que también promueven el desarrollo de habilidades blandas como la creatividad, la resolución de problemas y el aprendizaje colaborativo.

    .titulo-figura(data-aos="fade-right")
      h5 Tabla 2. 
      span Cuadro comparativo de herramientas de autor interactivas

    .tabla-a-1.mb-5(data-aos="fade-left") 
      table
        thead.text-center
          tr
            th Herramienta
            th Descripción
            th Ventajas principales
            th Competencias que fortalece
        tbody
          tr
            td.text-bold Genially
            td Plataforma online para crear recursos visuales e interactivos como infografías, presentaciones, juegos y mapas conceptuales animados.
            td
              ul.lista-ul--color.mb-0
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Interfaz intuitiva.
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Amplia variedad de plantillas.
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Ideal para storytelling visual.
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Permite incrustar contenido multimedia.
             
            td
              ul.lista-ul--color.mb-0
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Creatividad digital.
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Comunicación visual.
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Pensamiento narrativo.
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Diseño de materiales atractivos.
               

          tr
            td.text-bold H5P
            td Herramienta de código abierto para generar actividades interactivas (quizzes, presentaciones, líneas de tiempo, juegos). Se integra con Moodle, WordPress y otras plataformas LMS.
            td
              ul.lista-ul--color.mb-0
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Gratuita y personalizable.
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Fácil integración con LMS.
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Alta reutilización de contenidos.
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Accesible y compatible con estándares.
             
            td
              ul.lista-ul--color.mb-0
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Diseño instruccional.
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Evaluación formativa.
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Competencia digital docente.
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Gestión de recursos interactivos.
              

          tr
            td.text-bold Articulate Storyline
            td Software profesional para la creación de cursos en línea interactivos, con rutas personalizadas, simulaciones, cuestionarios y narraciones.
            td
              ul.lista-ul--color.mb-0
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Alta personalización.
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Profesional en diseño instruccional.
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Resultados SCORM para LMS.
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Ideal para e-learning corporativo.
             
            td
              ul.lista-ul--color.mb-0
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Pensamiento lógico.
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Planeación instruccional avanzada.
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Diseño centrado en el usuario.
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 Resolución de problemas técnicos.

    h3(data-aos="fade-down") Ejemplo aplicado: desarrollo de un módulo virtual para el fortalecimiento de habilidades de liderazgo educativo
    p(data-aos="fade-down") Una universidad ofrece un curso virtual sobre “Liderazgo Transformacional”, como parte de su especialización en “Gestión Educativa”. En este marco, se plantea el diseño de un módulo interactivo que promueva la participación activa, el pensamiento crítico y la reflexión ética.

    .bg-full-width.bg-fondo-slider.mb-5(data-aos="fade-right")
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img.img-a.img-t(src="@/assets/curso/temas/38.png")          
            .col-lg-7
              h5 Genially 
              ul.lista-ul--color
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 #[b Inicio del módulo:] presentación animada tipo storytelling basada en un caso real de liderazgo escolar exitoso. 
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 #[b Propósito:] activar conocimientos previos, motivar y contextualizar el tema. 
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 #[b Habilidad blanda promovida:] comunicación efectiva y empatía.      

          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img.img-a.img-t(src="@/assets/curso/temas/39.png")          
            .col-lg-7
              h5 H5P 
              ul.lista-ul--color
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 #[b Actividad de exploración:] línea de tiempo interactiva con hitos históricos del liderazgo en educación, incluyendo un cuestionario de opción múltiple. 
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 #[b Propósito:] explorar enfoques, reflexionar y validar la comprensión.
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 #[b Habilidad blanda promovida:] Pensamiento crítico y autogestión.

          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img.img-a.img-t(src="@/assets/curso/temas/40.png")          
            .col-lg-7
              h5 Articulate Storyline  
              ul.lista-ul--color
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 #[b Cierre del módulo:] simulación donde el estudiante toma decisiones ante un conflicto escolar.
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 #[b Propósito:] evaluar competencias a través de resolución de problemas en contextos reales.
                li.mb-3.d-flex
                  i.far.fa-arrow-alt-circle-right.color-1
                  p.mb-0 #[b Habilidad blanda promovida:] Toma de decisiones, liderazgo y resolución de conflictos.

    h3(data-aos="fade-down") Principios de diseño instruccional en recursos digitales
    p(data-aos="fade-down").mb-5 El diseño instruccional digital, es un proceso sistemático que busca optimizar la experiencia de aprendizaje, mediante la planificación intencional de contenidos, actividades y herramientas tecnológicas. Su aplicación permite construir recursos coherentes, significativos y alineados con los resultados de aprendizaje, atendiendo tanto a las necesidades cognitivas como afectivas, del estudiante.
    .bg-full-width-1.bg-fondo-1(data-aos="fade-right")
      .px-4.px-md-5.pb-md-3
        .row.justify-content-center       
          .col-lg-8
            SlyderF.text-center(columnas="col-12 col-lg-6")
              .bg-color-white.p-4.h-100.sha.brounded-sm
                img(src='@/assets/curso/temas/43.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.mb-4 Alineación pedagógica  
                p Asegura la coherencia entre objetivos, contenidos, estrategias y evaluación. Garantiza que todas las actividades contribuyan a los aprendizajes esperados.            
              .bg-color-white.p-4.h-100.sha.brounded-sm
                img(src='@/assets/curso/temas/42.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.mb-4 Segmentación cognitiva  
                p Divide el contenido en bloques temáticos para facilitar su comprensión y evitar la sobrecarga cognitiva. Ideal en contextos asincrónicos.
              .bg-color-white.p-4.h-100.sha.brounded-sm
                img(src='@/assets/curso/temas/45.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.mb-4 Interactividad significativa   
                p Promueve la participación activa mediante tareas que requieren reflexión, resolución de problemas o toma de decisiones. Ejemplo: infografías interactivas.
              .bg-color-white.p-4.h-100.sha.brounded-sm
                img(src='@/assets/curso/temas/44.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.mb-4 Retroalimentación continua  
                p Ofrece respuestas inmediatas y constructivas que fortalecen la autorregulación y autonomía del estudiante durante el proceso de aprendizaje.
              .bg-color-white.p-4.h-100.sha.brounded-sm
                img(src='@/assets/curso/temas/46.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.mb-4 Usabilidad y accesibilidad  
                p Favorece la inclusión, asegurando que todos los estudiantes puedan interactuar con los recursos sin barreras tecnológicas o cognitivas.                                                                

          .col-lg-4
            figure
              img.img-a.img-t(src='@/assets/curso/temas/41.png', alt='')   

        .bg-full-width.bg-h85
          .px-4.px-md-5
            .row.justify-content-center.align-items-center
              .col-lg-12
                .row.justify-content-center.align-items-center
                  .col-lg-4(data-aos="zoom-in")
                    img.img-a.img-t(src='@/assets/curso/temas/47.svg', alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0               
                  .col-lg-8(data-aos="fade-left").mb-3.mb-lg-0
                    p.mb-0.text-white.mt-5 El uso de herramientas como Genially, H5P y Articulate Storyline, permite integrar estos principios de forma eficaz, creando experiencias de aprendizaje dinámicas, accesibles y centradas en el desarrollo de competencias blandas clave para el liderazgo educativo. Así, el diseño instruccional en entornos digitales, deja de ser un aspecto técnico para convertirse en una estrategia pedagógica transformadora, especialmente en contextos de educación superior. 

    .titulo-figura(data-aos="fade-right")
      h5 Tabla 3. 
      span Principios de diseño instruccional en recursos digitales

    .tabla-a-1.mb-5(data-aos="fade-left") 
      table
        thead.text-center
          tr
            th Principio
            th Objetivo
            th Ejemplo aplicado
        tbody
          tr
            td.text-bold Alineación pedagógica
            td Garantizar coherencia entre objetivos, contenidos, actividades y evaluación.                               
            td Crear una secuencia donde los objetivos estén alineados con las actividades y la rúbrica de evaluación.

          tr
            td.text-bold Segmentación cognitiva
            td Dividir el contenido en bloques temáticos comprensibles.                               
            td Organizar una presentación en Genially con 4 secciones: introducción, teoría, ejemplos y actividad final.

          tr
            td.text-bold Interactividad significativa
            td Promover participación activa y reflexión crítica.                               
            td Diseñar en H5P una actividad de “elige tu camino” donde el estudiante toma decisiones sobre un caso real.

          tr
            td.text-bold Retroalimentación continua
            td Mejorar el aprendizaje mediante comentarios inmediatos y formativos.                               
            td Incluir cuestionarios con respuestas explicativas automáticas, en cada tema trabajado. 

          tr
            td.text-bold Usabilidad y accesibilidad
            td Asegurar que todos los estudiantes puedan acceder y usar el recurso.                               
            td Diseñar recursos accesibles desde móviles, con texto alternativo. en imágenes y subtítulos en videos.               

    h3(data-aos="fade-down") Estrategias para el desarrollo de materiales accesibles e inclusivos
    p(data-aos="fade-down").mb-5 Diseñar materiales educativos accesibles e inclusivos en entornos virtuales implica En la educación virtual, construir experiencias formativas accesibles no es una opción, es una responsabilidad. Cada estudiante merece encontrar en los contenidos una oportunidad real para aprender, participar y crecer. Por eso, en este espacio te presentamos algunas estrategias clave para diseñar materiales inclusivos que marcan la diferencia.

    .bg-full-width.bg-fondo-slider.mb-5(data-aos="fade-left")
      .p-4.p-md-5
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/9cqLwqWDCzs?si=F1b2M6SlLRnGqFf9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    h3(data-aos="fade-down") Ejemplo aplicado: diseño inclusivo de un módulo sobre comunicación asertiva en educación
    p(data-aos="fade-down") Un grupo de docentes en formación virtual, cursa la asignatura “Habilidades Comunicativas para el Liderazgo Educativo”. Se requiere desarrollar un módulo accesible e inclusivo para que todos los participantes, con diferentes estilos de aprendizaje y posibles condiciones de discapacidad, puedan acceder al contenido y participar activamente.

    .bg-full-width.bg-color-info.mb-5(data-aos="fade-right")
      .p-4.p-md-5
        .row.justify-content-center.align-items-center.mb-5
          .col-lg-10
            ImagenInfografica.color-secundario
                template(v-slot:imagen)
                  figure
                    img(src='@/assets/curso/temas/48.svg', alt='', style="max-width: 1106px;").mx-auto

                .bg-color-white.box-shadow.p-3(x="22.9%" y="85.6%" numero="+")
                  h5 Infografía interactiva
                  p Realizada en Genially, incluye texto alternativo para cada imagen, tipografía legible, fondo contrastante y navegación sencilla para lector de pantalla.

                .bg-color-white.box-shadow.p-3(x="22.1%" y="45.3%" numero="+")
                  h5 Actividad inicial
                  p Pregunta detonante con respuesta abierta en foro o mediante audio (para personas con dificultades motoras o de escritura).

                .bg-color-white.box-shadow.p-3(x="33.3%" y="19.2%" numero="+")
                  h5 Contenido teórico
                  p Se presenta en tres formatos: PDF accesible con etiquetas estructuradas, video explicativo con subtítulos en español y audio descargable, para escuchar sin conexión.

                .bg-color-white.box-shadow.p-3(x="62%" y="19.2%" numero="+")
                  h5 Evaluación formativa
                  p Cuestionario H5P con retroalimentación inmediata, navegación por teclado y compatible con lectores de pantalla.

                .bg-color-white.box-shadow.p-3(x="72.9%" y="41.4%" numero="+")
                  h5 Actividad de integración
                  p Reto colaborativo: crear un video o infografía sobre un caso de comunicación en el aula. Se permite entregar en distintos formatos (texto, voz, video o presentación).

                .bg-color-white.box-shadow.p-3(x="72.4%" y="85.7%" numero="+")
                  h5 Retroalimentación docente
                  p Personalizada mediante audio y texto, con posibilidad de videollamada para quienes requieran acompañamiento adicional.

    .bg-color-1.mb-5
      .row.justify-content-center.align-items-center
        .col-lg-7(data-aos="fade-left")
          .p-3
            h5 Las habilidades blandas desarrolladas son:
            ul.lista-ul--color
              li.mb-3.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Empatía y comunicación efectiva (al trabajar con la diversidad).
              li.mb-3.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Autonomía y autorregulación (al elegir el formato de aprendizaje).
              li.mb-3.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Creatividad digital (al crear recursos propios con herramientas accesibles).
              li.mb-3.d-flex
                i.far.fa-arrow-alt-circle-right.color-1
                p.mb-0 Colaboración inclusiva (al integrar compañeros con distintas capacidades).
        .col-lg-5(data-aos="zoom-in")
          img(src='@/assets/curso/temas/49.svg',alt="")

    h3(data-aos="fade-down") Valor pedagógico del ejemplo
    p(data-aos="fade-down") Este modelo de diseño no solo garantiza el acceso universal, sino que fortalece una práctica pedagógica ética, reflexiva y adaptativa. Permite que los estudiantes vivan la inclusión desde su rol de aprendices, para luego replicarla como diseñadores de experiencias educativas, formando profesionales capaces de liderar transformaciones significativas en educación digital.

    .bg-full-width.bg-color-3.mb-5
      .px-4.p-md-5
        .row.justify-content-center.align-items-center 
          .col-lg-4.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/temas/50.png', alt='')                  
          .col-lg-8
            h2.mb-4(data-aos="flip-up") Estrategias de comunicación y participación en entornos virtuales
            p.mb-4(data-aos="fade-right") Se invita a leer el documento “Estrategias de comunicación y participación en entornos virtuales”, donde se aborda el papel central que desempeña la comunicación pedagógica en contextos educativos en línea. 
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_1.docx')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Estrategias de comunicación y participación en entornos virtuales

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
              a(href="https://www.eumed.net/rev/atlante/2018/07/plataformas-virtuales-educacion.html" target="_blank" rel="noopener noreferrer") Barrera Rea, V. F., & Guapi Mullo, A. (2018). La importancia del uso de las plataformas virtuales en la educación superior. Revista Atlante: Cuadernos de Educación y Desarrollo.
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.redalyc.org/journal/290/29063446026/html/" target="_blank" rel="noopener noreferrer") Cuantindioy Imbachi, J., González Palacio, L., Muñoz Realpe, J. D., & Díaz Cardona, I. (2019). Plataformas virtuales de aprendizaje: Análisis desde su adaptación a estilos de aprendizaje. Revista Venezolana de Gerencia.             

            p.d-flex.my-4
              img.me-3(src='@/assets/template/book.svg' :style="{'max-width':'16px'}")
              a(href="https://infanciayfamilias.castillalamancha.es/sites/default/files/2022-04/Guia-entornos-educativos-digitales-inclusivos-y-accesibles.pdf" target="_blank" rel="noopener noreferrer") FIAPAS. (2021). Entornos educativos digitales inclusivos y accesibles: Guía para el apoyo a la comunicación oral del alumnado con sordera. Confederación Española de Familias de Personas Sordas (FIAPAS). 
            p.d-flex.my-4
              img.me-3(src='@/assets/template/book.svg' :style="{'max-width':'16px'}")
              a(href="https://www.mineducacion.gov.co/1621/articles-339097_archivo_pdf_competencias_tic.pdf" target="_blank" rel="noopener noreferrer") Ministerio de Educación Nacional de Colombia. (2013). Competencias TIC para el desarrollo profesional docente. Ministerio de Educación Nacional.           

            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=l-UyknGzFsg" target="_blank" rel="noopener noreferrer") Amaya Alvear, H. (2021). Herramientas en la Gestion de la Informacion .
            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://youtu.be/oShN5MHsxjU" target="_blank" rel="noopener noreferrer") Educar Portal. (2020). Microaprendizaje: ¿ qué es trabajar colaborativamente?              

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')
  
  </template>

<script>
import Actividad from '@/components/actividad/Actividad.vue'
export default {
  name: 'Tema2',
  components: {
    Actividad,
  },
  data() {
    return {
      cuestionario: {
        tema: 'DISEÑO DE ENTORNOS VIRTUALES DE APRENDIZAJE',
        titulo: 'Ponte a prueba',
        introduccion:
          'Demuestra lo que aprendiste en esta unidad y pon a prueba tus conocimientos.',
        barajarPreguntas: true,
        preguntas: [
          {
            id: 1,
            texto:
              '¿Cuál de los siguientes elementos es fundamental para garantizar la accesibilidad en un Entorno Virtual de Aprendizaje?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Uso exclusivo de materiales en formato PDF',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto:
                  'Implementación de subtítulos y descripciones en imágenes',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'Eliminación de herramientas interactivas',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Restricción del acceso a usuarios sin discapacidad',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 2,
            texto:
              '¿Qué modelo instruccional estructura el diseño de aprendizaje en cinco fases: ¿Análisis, Diseño, Desarrollo, Implementación y Evaluación?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Conectivismo',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Modelo ADDIE',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'Aprendizaje basado en problemas',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Teoría del aprendizaje experiencial',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 3,
            texto:
              '¿Cuál es una ventaja clave del aprendizaje adaptativo en entornos digitales?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto:
                  'Permite que todos los estudiantes avancen al mismo ritmo',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Restringe el acceso a ciertos contenidos',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto:
                  'Personaliza la experiencia educativa según el progreso del estudiante',
                esCorrecta: true,
              },
              {
                id: 'd',
                texto: 'Reduce la interacción entre estudiantes y docentes',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 4,
            texto:
              '¿Qué herramienta permite analizar el comportamiento de los estudiantes en un Entorno Virtual de Aprendizaje?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Gamificación',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Analítica del Aprendizaje',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'Evaluación sumativa',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Aprendizaje colaborativo',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 5,
            texto:
              '¿Cuál de las siguientes estrategias fomenta la inclusión en la educación digital?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto:
                  'Uso de una única metodología para todos los estudiantes',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto:
                  'Implementación del Diseño Universal para el Aprendizaje (DUA)',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'Exclusión de estudiantes con necesidades especiales',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Eliminación de herramientas de accesibilidad',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
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
