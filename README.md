# CAPÍTULO V . PRODUCT IMPLEMENTATION, VALIDATION & DEPLOYMENT

5.1. Software Configuration Management.
5.1.1. Software Development Environment Configuration.

Esta sección detalla las herramientas utilizadas durante el desarrollo del software, organizadas según las distintas fases del proyecto.

*Project Management

-Google Meet: https://meet.google.com/

-Plataforma utilizada para realizar reuniones virtuales con los miembros del equipo. Permite compartir pantalla, imágenes, texto y video, todo en tiempo real. Es compatible con navegadores web, dispositivos móviles y computadoras, y solo requiere una cuenta activa para su uso.

-Trello: https://trello.com/home

-Herramienta visual para la gestión de tareas del proyecto. Nos permite organizar y hacer seguimiento a tareas pendientes, en proceso y completadas. Su interfaz por tableros facilita la coordinación y visibilidad del avance del equipo. Se accede fácilmente desde un navegador tras crear una
 cuenta.

*Requirement Management

-Trello: https://trello.com/home

También lo empleamos para gestionar los requisitos del sistema. Su diseño intuitivo permite trabajar colaborativamente en el backlog, definir prioridades y alinear los objetivos del equipo con las funcionalidades a desarrollar.

-Product UX/UI Design

-UXpressia: https://uxpressia.com/

Fue clave para construir perfiles detallados de usuarios, mapear sus emociones, metas y comportamientos mediante herramientas como User Personas, Journey Maps y Empathy Maps.

-Figma: https://www.figma.com/
Plataforma colaborativa de diseño usada para crear wireframes y mockups. Su facilidad para compartir y editar en tiempo real la convirtió en una herramienta fundamental en el desarrollo de interfaces visuales.

*Software Development

-Landing Page

Se desarrolló la landing page con tecnologías como HTML5, CSS3 y JavaScript, apoyados en Bootstrap para lograr un diseño responsivo y acelerar el desarrollo de una interfaz adaptable a diversos dispositivos.

*IDE’s de desarrollo

-Visual Studio Code: https://code.visualstudio.com/

Usamos este IDE por su rendimiento, facilidad de uso y herramientas integradas para la edición, depuración y control de versiones. Fue esencial para implementar la landing page de forma ágil y ordenada.

-GitHub: https://github.com/

Plataforma para alojar el repositorio del proyecto y gestionar el control de versiones del código fuente y la documentación, facilitando la colaboración y el seguimiento de cambios.

*Software Deployment

-GitHub Pages

Utilizamos GitHub Pages para desplegar la landing page de forma gratuita y directamente desde el repositorio del proyecto. Esta herramienta permite alojar sitios estáticos fácilmente, integrándose con el flujo de trabajo de GitHub y facilitando una publicación continua con cada cambio en el repositorio.

*Software Documentation

-Google Drive: https://drive.google.com/drive/home

Utilizamos Google Docs para redactar y mantener la documentación del proyecto de forma colaborativa. Esta herramienta facilita la edición en tiempo real entre los miembros del equipo, asegurando que toda la información esté organizada y accesible desde cualquier dispositivo.

-Canva: https://www.canva.com/

Empleamos Canva para la creación de material visual y presentaciones gráficas del proyecto. Su interfaz sencilla e intuitiva permite diseñar documentos importantes que ayudan a comunicar ideas de forma clara y profesional.

-Markdown:

Un lenguaje de marcado ligero y sencillo para crear documentos con formato, empleándose para redactar la documentación del proyecto de manera clara y estructurada.

5.1.2. Source Code Management.

El proyecto se desarrolló en GitHub, donde se creó una organización dedicada con repositorios específicos para cada módulo del sistema, cada uno estructurado con sus respectivas ramas. Esta plataforma facilitó la gestión del código fuente, el control de versiones y la colaboración entre los 

desarrolladores. Durante los sprints futuros, se implementará la metodología Git Flow para mantener una estructura de trabajo ordenada, permitiendo una integración controlada de nuevas funcionalidades, correcciones y lanzamientos. Esta combinación garantiza un flujo de trabajo eficiente y 

una coordinación efectiva dentro del equipo de desarrollo.

*Repositorios GitHub

Los repositorios de GitHub que utilizaremos para cada uno de los productos del proyecto son los siguientes:

-Landing Page: https://github.com/MediTecOpen/LandingPage

-Documentacion: https://github.com/MediTecOpen/docs

-Frontend: https://github.com/MediTecOpen/Frontend

5.1.3. Source Code Style Guide & Conventions.

Para asegurar un código ordenado, consistente y alineado con estándares reconocidos, en nuestro proyecto adoptamos el Google HTML/CSS Style Guide. Esta guía nos permite escribir HTML y CSS de forma clara y estructurada. Entre las convenciones que aplicaremos se encuentran:

-Utilizar dos espacios para la indentación, tanto en HTML como en CSS, lo que favorece la claridad sin generar un código innecesariamente ancho.

-Seguir un orden lógico en los selectores CSS, empezando por los de tipo, luego los ID y finalmente las clases.

-Nombrar las clases con términos breves pero descriptivos, empleando guiones bajos como separadores para mejorar la comprensión.

-Agregar comentarios puntuales cuando sea necesario explicar reglas CSS que podrían no ser evidentes de inmediato.

En cuanto a JavaScript, seguiremos el Google JavaScript Style Guide para mantener un código limpio y fácil de mantener.

 Estas son algunas de las prácticas que implementaremos:

-Declarar variables inmutables con const y aquellas que pueden cambiar con let, evitando el uso de var para prevenir ambigüedades en el alcance.

-Adoptar la notación camelCase para nombrar variables, funciones y métodos, mejorando la legibilidad.

-Ubicar las declaraciones de variables al inicio de funciones o bloques para evitar problemas derivados del hosting.

-Priorizar funciones con nombre en lugar de funciones anónimas, con el fin de facilitar el rastreo de errores y mejorar la depuración.

-Emplear template strings para concatenar textos, haciendo el código más limpio y fácil de leer cuando se insertan expresiones.

5.1.4. Software Deployment Configuration.

El desarrollo del Landing Page se realiza utilizando HTML, CSS y JavaScript. Estos archivos deben estar en la raíz del repositorio o en la carpeta docs, dependiendo de la configuración elegida para GitHub Pages.

1.Configuración de GitHub Pages:

-Dirígete a la configuración del repositorio en GitHub:

-Ve a la pestaña Settings.

-Desplázate hacia abajo hasta la sección GitHub Pages.

-En el menú desplegable "Source", selecciona la rama main o master y la carpeta raíz (/root) o docs/ si los archivos están organizados dentro de esa carpeta.

-Una vez seleccionado, GitHub Pages generará una URL para acceder a tu sitio web.

2.Subir y actualizar los archivos al repositorio:

Una vez que los archivos del proyecto estén listos, súbelos al repositorio. Para ello, puedes usar los siguientes comandos:

-git add .

-git commit -m "Subida inicial del proyecto"

-git push origin main

3.Verificar el despliegue:

Después de haber configurado GitHub Pages y haber subido los archivos, espera unos minutos para que el sitio se despliegue. GitHub te proporcionará un enlace donde podrás verificar que el sitio web está activo.

En este caso, el Link del Landing Page desplegado es: https://asi0385-1775-meditec.github.io/landing-page/

Landing Page

5.2. Landing Page, Services & Applications Implementation.

5.2.1. Sprint 1

5.2.1.1. Sprint Planning 1.

En este primer sprint, el equipo se reunió para definir el alcance del desarrollo inicial del proyecto. El objetivo principal es sentar las bases de una aplicación efectiva y bien estructurada, comenzando con la creación de una página de aterrizaje (landing page). Esta página será el primer 

punto de contacto con los usuarios, permitiendo validar las ideas iniciales del producto y medir el interés del público objetivo. Al establecer una presencia digital sólida desde las primeras etapas, se facilitará la recolección de feedback valioso y la generación de tracción desde el inicio

 del proyecto.


## 📝 Sprint 1 - Planning Summary

| **Elemento**                        | **Detalle**                                                                                                   |
|------------------------------------|---------------------------------------------------------------------------------------------------------------|
| **Sprint Planning Background**     |                                                                                                               |
| 📅 **Date**                         | 20-04-2024                                                                                                    |
| 🕕 **Time**                         | 18:00 PM                                                                                                      |
| 📍 **Location**                     | Videoconferencia mediante Google Meet                                                                         |
| 🧾 **Prepared By**                  | Jack Roque, Johan Bottger, Gabriel Lapa de la Cruz, Juan Santos, Stanley Gutierrez                            |
| 👥 **Attendees**                    | Jack Roque, Johan Bottger, Gabriel Lapa de la Cruz, Juan Santos, Stanley Gutierrez                            |
| **Sprint n Review Summary**        | N.A.                                                                                                          |
| **Sprint n Retrospective Summary** | N.A.                                                                                                          |

---

### 🎯 Sprint Goal and User Stories

Nuestro enfoque está en diseñar e implementar una página de inicio (landing page) responsiva y fácil de usar, con secciones claras para cuidadores, personas dependientes, contacto, sobre nosotros, ayuda e inicio de sesión/registro.

Creemos que esto proporcionará una experiencia de usuario intuitiva y fluida tanto para cuidadores como para personas dependientes y visitantes, permitiéndoles navegar fácilmente y acceder a las funcionalidades clave.

Esto se confirmará cuando la landing page esté completamente funcional, optimizada para diferentes dispositivos y reciba comentarios positivos por parte de los usuarios en base a pruebas de usabilidad y métricas.

---

| **Métrica**               | **Valor** |
|---------------------------|-----------|
| 🔢 **Sprint 1 Velocity**   | 12        |
| 📌 **Sum of Story Points**| 12        |

5.2.1.2. Aspect Leaders and Collaborators.

En el Sprint 1 se definieron los siguientes aspectos clave para la implementación del Landing Page:

-UI/UX Design

-Desarrollo HTML/CSS

-Desarrollo JavaScript

-Documentación de Servicios

-Despliegue

A continuación la matriz de Liderazgo y Colaboración (LACX), donde “L” indica el líder de cada aspecto y “C” a sus colaboradores:

## 👨‍💻 Asignación de Roles del Equipo

| **Miembro del Equipo**               | **Usuario GitHub** | **UI/UX Design** | **HTML/CSS** | **JavaScript** | **Servicios** | **Despliegue** |
|-------------------------------------|--------------------|------------------|--------------|----------------|----------------|----------------|
| Roque Tello, Jack Eddie             | UPC-Skylar         | C                | L            | L              | C              | L              |
| Santos Torres, Juan Manuel          | JuanManuel312      | C                 | C            | C              | C              | C              |
| Bottger Salazar, Johan Karl         | Deskjobo           | C                | C            | C              | C              | C              |
| Gutierrez Tume, Stanley Jeremy      | Stan-gt213891      | C                 | C            | C              | C              | C              |
| Lapa de la Cruz, Gabriel Omar       | Gabo0722           | L                | C            | C              | C              | C              |

**Leyenda**:
- **L** = Líder
- **C** = Colaborador

5.2.1.3. Sprint Backlog 1

El Sprint Backlog 1 representa la lista de tareas y elementos de trabajo priorizados para la primera iteración del proyecto. En esta fase inicial, el enfoque principal es construir los componentes esenciales de la landing page, asegurar una experiencia de usuario fluida y establecer una base

 sólida para las futuras iteraciones. El objetivo es crear una landing page atractiva y funcional que permita a los usuarios registrarse, conocer la misión de la startup y navegar de manera intuitiva, mientras se incorporan funcionalidades críticas como formularios de contacto y optimización

 para dispositivos móviles.

## ✅ Sprint 1 - Tareas y Progreso

| **User Story ID** | **Título Historia de Usuario**      | **Task ID** | **Título de Tarea**       | **Descripción**                                                                 | **Estimación** | **Asignado a**                | **Estado** |
|-------------------|-------------------------------------|-------------|----------------------------|----------------------------------------------------------------------------------|----------------|-------------------------------|------------|
| 24                | Contenido de Landing Page           | 01          | Estructura                 | Desarrollar la estructura del landing page siguiendo los lineamientos de estilo | 3 hrs          | Jack Eddie Roque Tello        | Done       |
| 24                | Contenido de Landing Page           | 02          | Contenido                  | Poblar la landing page con información relevante sobre servicio                 | 2 hrs          | Jack Eddie Roque Tello        | Done       |
| 23                | Registro desde Landing Page         | 03          | Opción Registrarse         | Implementar funcionalidad de botón de registro                                  | 2 hrs          | Jack Eddie Roque Tello        | Done       |
| 23                | Registro desde Landing Page         | 04          | Formulario de Registro     | Desarrollar formulario de registro                                              | 3 hrs          | Jack Eddie Roque Tello        | Done       |
| 22                | Diseño responsive                   | 05          | Responsive Web Page        | Configurar la landing page de manera responsiva para distintos dispositivos     | 2 hrs          | Jack Eddie Roque Tello        | Done       |


5.2.1.4. Development Evidence for Sprint Review.

En esta parte, mostramos el proceso que seguimos para diseñar y mantener actualizada la landing page.

| **Branch**                | **Commit ID**        | **Mensaje de Commit**                       | **Fecha**       |
|---------------------------|----------------------|----------------------------------------------|-----------------|
| develop                   | 5864622…0865a5f      | Add first version                            | 24-04-2025      |
| feature/caregivers        | 752c40d…75ad395      | feat: add caregivers html and css            | 23-04-2025      |
| feature/dependent-persons | be67e9d…c06272d      | feat: add dependent persons html and css     | 23-04-2025      |
| feature/home              | 0fc968d…3ad04d1      | feat: add dependent home html and css        | 23-04-2025      |
| feature/login             | 0fc968d…59e5941      | feat: add dependent login html and css       | 22-04-2025      |


| **Branch** | **Commit ID**        | **Mensaje de Commit**                   | **Fecha**       |
|------------|----------------------|------------------------------------------|-----------------|
| Cap1       | 5864622…0865a5f      | Update README.md                         | 25-04-2025      |
| Cap2       | 752c40d…75ad395      | feat: add User Persona                   | 25-04-2025      |
| Cap3       | be67e9d…c06272d      | Update README.md                         | 25-04-2025      |
| Cap4       | 0fc968d…3ad04d1      | Update README.md                         | 25-04-2025      |
| Cap5       | 0fc968d…59e5941      | Capitulo 5 primer commitE.md             | 25-04-2025      |

5.2.1.5. Execution Evidence for Sprint Review

Durante el Sprint 1, se logró implementar completamente la landing page de la aplicación, cumpliendo con todos los criterios de aceptación definidos en las historias de usuario. El equipo desarrolló un sitio web funcional, atractivo y adaptable a diferentes dispositivos, incluyendo secciones

 clave como el registro e inicio de sesión, información del equipo y misión de la startup, formularios de contacto, secciones especializadas para cuidadores y personas dependientes. Este entregable constituye un primer paso fundamental para validar el producto con usuarios reales y 

establecer una presencia sólida en línea

## ✅ Historias de Usuario - Sprint 1

| **Epic / Story ID** | **Título**                     | **Criterios de Aceptación**                                                                                                                                                   |
|---------------------|--------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| US24                | Contenido de la landing page   | DADO QUE el usuario está en la página principal, CUANDO haga clic en cualquier ítem del menú, ENTONCES va redirigido a la sección correspondiente.                            |
| US23                | Registro desde Landing Page    | DADO QUE el usuario está en el landing page de CareMe, CUANDO hace clic en “Iniciar sesión” o “Registrarse”, ENTONCES el sistema lo redirige al formulario correspondiente.  |
| US22                | Diseño responsive              | DADO QUE el usuario está en el landing page de CareMe, CUANDO accede desde un dispositivo móvil o escritorio, ENTONCES el sistema adapta el diseño correctamente.            |


5.2.1.6. Services Documentation Evidence for Sprint Review.

En este Sprint, el foco estuvo centrado exclusivamente en el desarrollo del frontend estático (Landing Page) del proyecto CareMe. Por esta razón, no se han trabajado endpoints ni funcionalidades relacionadas con servicios web o APIs RESTful.

La documentación de Web Services utilizando OpenAPI/Swagger será considerada en futuros Sprints, una vez que se inicie la implementación del backend del sistema.

5.2.1.7. Software Deployment Evidence for Sprint Review.

Durante este Sprint, se llevó a cabo el despliegue de la landing page del proyecto CareMe, como primer paso en la publicación progresiva de los productos del sistema. Esta actividad se enmarca dentro del objetivo de validar visualmente los avances de diseño e interacción con el cliente y 

equipo docente.

Actividades Realizadas:

-Configuración del repositorio GitHub y estructura inicial de carpetas.

-Implementación de flujo de trabajo con Git Flow, manteniendo los cambios en la rama develop.

-Realización de un merge desde develop hacia la rama main, de acuerdo a las convenciones definidas en la sección 5.1.2.

-Activación de GitHub Pages como servicio de despliegue estático, apuntando al contenido de la rama main.

-Publicación exitosa de la landing page accesible a través de una URL pública.

Link del Landing Page desplegado en : https://meditecopen.github.io/LandingPage/

5.2.1.8. Team Collaboration Insights during Sprint. 

-Se proporcionarán detalles sobre la colaboración y la comunicación dentro del equipo de desarrollo durante el sprint. Esto incluirá la coordinación de esfuerzos entre los miembros del equipo, la resolución de problemas y la gestión de tareas. También se destacarán las lecciones aprendidas y

las oportunidades de mejora en la colaboración.

-Todos los miembros del equipo trabajamos para realizar este trabajo de manera correcta, estableciendo fechas de entrega y ayudándonos entre si para cualquier duda que tengamos.

-Tuvimos reuniones por la plataforma google meet.

5.2.2. Sprint 2
 5.2.2.1.Sprint Planning 2

## 📝 Sprint 2 - Resumen de Planeación

| **Elemento**                        | **Detalle**                                                                                                               |
|------------------------------------|---------------------------------------------------------------------------------------------------------------------------|
| 📅 **Fecha**                        | 13-05-2024                                                                                                                |
| 🕕 **Hora**                         | 17:00 PM                                                                                                                  |
| 📍 **Lugar**                        | Videoconferencia mediante Google Meet                                                                                     |
| 🧾 **Preparado por**                | Roque Tello, Jack Eddie                                                                                                   |
| 👥 **Participantes**                | Roque Tello, Jack Eddie                                                                                                   |
| ✅ **Resumen Sprint 1 Review**      | Implementación de la aplicación web (Business Website) de CareMe.                                                         |
| 🔁 **Resumen Sprint 1 Retrospective** | Si bien hubo complicaciones en las coordinaciones grupales con el equipo, se logró cumplir con todos los requisitos. Para mejorar, se sugiere mayor compromiso y comunicación. |

---

### 🎯 Objetivo del Sprint 2 y User Stories

> Nuestro enfoque está en desarrollar y desplegar la primera versión de la aplicación web Frontend, con soporte multilenguaje y funcionalidades CRUD, incluyendo también una nueva versión de la landing page.  

> Creemos que esto ofrecerá una experiencia de usuario fluida, mejorará el compromiso de los usuarios y facilitará el acceso al permitir soporte multilingüe, además de una aplicación funcional que interactúe con APIs.  

> Esto se confirmará cuando la nueva versión de la Landing Page esté desplegada correctamente, la aplicación web frontend esté funcional con soporte multilingüe (ngx-translate) y las operaciones CRUD estén integradas y probadas.

---

| **Métrica**               | **Valor** |
|---------------------------|-----------|
| 🔢 **Sprint 2 Velocity**   | 12        |
| 📌 **Sumatoria de Story Points** | 12        |


 5.2.2.2. Aspect Leaders and Collaborators
En este proyecto, CareMe, he sido el único colaborador, Jack Eddie Roque Tello, quien ha liderado y ejecutado todo el trabajo en el segundo sprint. Durante este sprint, he desplegado la Frontend Web Application utilizando tecnologías clave como NGX-Translate, Angular Material, y Angular 

Router para garantizar una experiencia de usuario fluida y multilingüe.

Además, he desarrollado y desplegado una API que permite a los usuarios contactar con nosotros directamente desde la plataforma. He integrado esta API en la aplicación, lo que habilita a los usuarios a enviar métodos POST para enviar sus dudas o inquietudes. De este modo, como administrador,

 podemos visualizar las preguntas de los usuarios en tiempo real, mejorando la comunicación y el soporte dentro de la aplicación.

Gracias a estas implementaciones, la plataforma se vuelve más interactiva, accesible y eficiente, alineándose con los objetivos del proyecto CareMe de proporcionar un servicio completo y accesible a los usuarios, cuidadores y familias

 5.2.2.3.Sprint Backlog 2

## ✅ Sprint 2 - Tareas y Progreso

| **User Story ID** | **Título Historia de Usuario**                 | **Task ID** | **Título de Tarea**                          | **Descripción**                                                                                                       | **Estimación** | **Asignado a**                 | **Estado** |
|-------------------|------------------------------------------------|-------------|-----------------------------------------------|------------------------------------------------------------------------------------------------------------------------|----------------|-------------------------------|------------|
| 28                | Idiomas disponibles para la plataforma         | 01          | Integrar ngx-translate para traducción         | Implementar ngx-translate para traducir las páginas principales (home, caregivers, etc.) entre español e inglés.      | 2 hrs          | Jack Eddie Roque Tello        | Done       |
| 28                | Idiomas disponibles para la plataforma         | 02          | Crear archivos JSON para idiomas              | Crear y completar los archivos de traducción en inglés (`en.json`) y español (`es.json`) para todas las vistas.       | 2 hrs          | Jack Eddie Roque Tello        | Done       |
| 29                | Método POST para consultas de usuarios         | 01          | Desarrollar el método POST en CaremeApiService | Crear el método POST en el servicio `CaremeApiService` para enviar los datos del formulario de contacto a la API.     | 2 hrs          | Jack Eddie Roque Tello        | Done       |
| 29                | Método POST para consultas de usuarios         | 02          | Implementar onSubmit en ContactComponent       | Implementar el método `onSubmit` en el componente de contacto para enviar los datos al servicio y manejar la respuesta.| 3 hrs          | Jack Eddie Roque Tello        | Done       |


 5.2.2.4.Development Evidence for Sprint Review

Para el desarrollo del proyecto hemos seguido la estructura enseñada en clase y los principios de Domain-Driven-Design:

5.2.2.5.Execution Evidence for Sprint Review

Durante el Sprint 2 se avanzó de forma significativa en el desarrollo e implementación de la Frontend Web Application de CareMe, cumpliendo con los objetivos establecidos en el Sprint Goal. A continuación, se detallan las evidencias que respaldan el trabajo realizado:

5.2.2.6.Services Documentation Evidence for Sprint Review

Para documentar adecuadamente la implementación de los servicios en el proyecto CareMe, se emplearon diversas herramientas de desarrollo centradas en la aplicación Front-End. El trabajo se realizó utilizando tecnologías de vanguardia y siguiendo las mejores prácticas de desarrollo para 

asegurar un producto de calidad.

*Herramientas y Tecnologías Empleadas:

-WebStorm: Se utilizó WebStorm como el IDE principal para el desarrollo, dada su integración con Angular, soporte completo para TypeScript, y funcionalidades avanzadas de depuración que facilitaron la implementación eficiente del código.

-Angular: El framework principal para la aplicación es Angular, elegido por su robustez y facilidad para manejar aplicaciones SPA (Single Page Applications), permitiendo la gestión eficiente del estado de la aplicación y las rutas dinámicas.

-ngx-translate: Para garantizar una experiencia de usuario internacionalizada, se implementó ngx-translate para manejar la traducción dinámica de la interfaz en varios idiomas (español e inglés). Esta herramienta permitió que la plataforma fuera accesible para usuarios de diferentes regiones.

-Angular Material: Para la creación de una interfaz de usuario moderna y accesible, se utilizó Angular Material. Este conjunto de componentes predefinidos permitió agilizar el diseño de interfaces atractivas y adaptables a distintas plataformas y dispositivos.

-Angular Router: Se utilizó Angular Router para la navegación dentro de la aplicación, asegurando una estructura fluida y eficiente para la transición entre componentes sin necesidad de recargar la página.

-Beeceptor: Para el desarrollo de la API, se utilizó Beeceptor, una herramienta que simula una API RESTful de manera sencilla. Esto permitió realizar pruebas y verificar el correcto envío de datos mediante POST en el formulario de contacto, sin necesidad de configurar un servidor real en esta fase.

*Evidencias de la Documentación:

-Prototipo en Figma: Se creó un prototipo interactivo en Figma que representa la estructura, diseño y flujo de navegación de la Landing Page de CareMe. Este prototipo permitió definir el diseño visual y las interacciones clave antes de iniciar el desarrollo. Además, se diseñaron las 

pantallas de registro, inicio de sesión, y otras secciones clave para el funcionamiento de la aplicación.

Enlace al prototipo: https://www.figma.com/design/zGaYnTarmHelTTlLmd3mZy/Untitled?node-id=0-1&t=3r5bAlEjcx2TmOLR-1 

-HTML y CSS: Estas tecnologías fueron empleadas para traducir el prototipo visual en código. Se utilizaron prácticas de desarrollo moderno y responsivo para garantizar que la aplicación se adapte correctamente a distintos dispositivos, especialmente en dispositivos móviles y escritorios.

-Responsividad: Se emplearon técnicas de Flexbox y CSS Grid para asegurar que los elementos se alinean correctamente en pantallas de distintos tamaños, mejorando la accesibilidad y experiencia del usuario.


*Tipografía y Diseño Visual:

Tipografía: Para lograr una identidad visual coherente y moderna, se seleccionó la tipografía Inter. Esta fuente fue elegida por su excelente legibilidad en dispositivos pequeños, así como por su estilo limpio y moderno que refuerza la identidad visual de CareMe.

-Consistencia en los Márgenes y Espaciados: Se implementaron márgenes y espaciados consistentes a lo largo de la plataforma, para asegurar una distribución equilibrada y una experiencia de usuario agradable.

-Estilo de Botones y Formularios: Se cuidaron los detalles de los botones y formularios, utilizando una combinación de estilos modernos de Angular Material para garantizar accesibilidad y coherencia con el diseño general de la interfaz.

Conclusión:
El uso de WebStorm, Angular, ngx-translate, Angular Material, y Beeceptor ha permitido desarrollar una solución sólida y funcional en este sprint. Gracias a estas herramientas y el enfoque centrado en el diseño, la aplicación CareMe se presenta como una plataforma moderna, accesible y con 

soporte para múltiples idiomas, lo que facilita su uso para una amplia variedad de usuarios.

5.2.2.7.Software Deployment Evidence for Sprint Review


Se utilizo GitHub pages para el despliegue de nuestra aplicación

5.2.2.8.Team Collaboration Insights during Sprint

Durante el Sprint 2, trabajé de manera individual en el desarrollo de la plataforma CareMe, lo que representó una mejora en términos de organización y entrega respecto al Sprint anterior. A continuación, se describen algunos aspectos clave de la dinámica de trabajo:

Trabajo individual: Durante este sprint, fui el único responsable del desarrollo, la documentación y el despliegue de la aplicación. Intenté comunicarme con mis compañeros de equipo para coordinar tareas y avances, pero no obtuve respuesta de su parte. A pesar de ello, tomé la iniciativa 

para avanzar en el proyecto de forma autónoma.

-Desarrollo y despliegue: Me encargué personalmente de todas las etapas del desarrollo y despliegue de la aplicación. Utilicé Angular, ngx-translate y Angular Material para el desarrollo de las funcionalidades, mientras que Beeceptor se empleó para simular la API y garantizar que los 

formularios de contacto pudieran enviar los datos correctamente. Todo esto fue implementado y desplegado exitosamente en este sprint.

-Documentación: Aunque trabajé solo, me aseguré de documentar de manera exhaustiva el desarrollo de la aplicación, incluyendo el uso de herramientas como Figma para la creación del prototipo y la integración de Angular Router. La documentación fue clave para garantizar que los aspectos 

técnicos y las decisiones de diseño fueran claras para cualquier revisión futura.

-Comunicación: Intenté establecer una comunicación continua con mis compañeros a través de WhatsApp y Google Meet para coordinar actividades y resolver dudas. Sin embargo, la respuesta fue mínima, lo que me obligó a gestionar todo el trabajo por mi cuenta. A pesar de esto, logré mantener un 

flujo de trabajo organizado y bien documentado.

-Lecciones aprendidas: Esta experiencia me enseñó la importancia de una comunicación activa dentro del equipo. En futuros sprints, sería ideal establecer canales de comunicación más claros y efectivos para asegurar la colaboración. Además, la asignación de tareas debe ser más equitativa y

 específica para evitar que un solo miembro del equipo cargue con la mayor parte del trabajo.

-Mejoras futuras: A pesar de haber trabajado de manera autónoma, se identificaron áreas para optimizar la colaboración, como la planificación más detallada de las tareas y el uso más efectivo de las herramientas colaborativas como GitHub y Slack.

*Conclusiones

-Desarrollo exitoso de la Landing Page: Durante el Sprint 2, se completó exitosamente el desarrollo de la Landing Page de CareMe. A pesar de trabajar de forma individual, se logró implementar todas las funcionalidades y características planificadas, proporcionando una experiencia de usuario

 sólida y coherente. La página se adaptó correctamente a dispositivos de diferentes tamaños gracias al uso de Angular Material y CSS responsive, lo que asegura un acceso óptimo para todos los usuarios.

-Capacidad de traducción de requisitos a código funcional: La implementación de la Landing Page demostró nuestra capacidad para traducir los requisitos funcionales y de diseño en código ejecutable. Se utilizaron tecnologías clave como Angular, ngx-translate para la internacionalización y 

Angular Router para la navegación, lo que resultó en una página fácil de usar y visualmente atractiva. Además, se utilizó Figma para el prototipado, lo que permitió mantener una alineación continua con el diseño original.

-Base sólida para el desarrollo futuro de la Web Application: La estructura y diseño de la Landing Page han establecido una base sólida para los siguientes pasos del proyecto. Esta implementación sienta las bases para la creación y expansión de la Web Application, que continuará 

evolucionando en etapas posteriores. La integración de formularios y la capacidad de interacción con el usuario, como el formulario de contacto, nos permitirá ofrecer una experiencia completa y funcional en el futuro.


-Retos de trabajo individual: Aunque el Sprint 2 fue un éxito, se identificaron varios desafíos al trabajar de manera autónoma, especialmente en términos de colaboración. La falta de interacción constante con los compañeros de equipo dificultó la asignación de tareas y la resolución de 

ciertos problemas. En el futuro, una mejor comunicación y colaboración serán fundamentales para optimizar el trabajo en equipo y la distribución de tareas.

-Lecciones aprendidas y mejoras para los próximos sprints: A lo largo del Sprint 2, aprendí la importancia de la planificación y la asignación clara de responsabilidades, especialmente cuando se trabaja de manera autónoma. Además, se destacó la importancia de establecer un plan de 

comunicación y coordinación más efectivo dentro del equipo para mejorar la colaboración en futuras fases del proyecto.

-En resumen, el Sprint 2 fue un hito importante para CareMe, ya que se logró el desarrollo exitoso de la Landing Page conforme a lo enseñado en el curso, sentando las bases para el siguiente nivel de la aplicación web. Sin embargo, el trabajo en equipo y la comunicación aún requieren mejoras

 para optimizar la colaboración en los próximos sprints.

5.2.3.   Sprint 3
5.2.3.1. Sprint Planning 3

En esta sección se detalla el proceso de planificación correspondiente al tercer sprint del proyecto. El equipo definió los objetivos a alcanzar durante este ciclo de trabajo, priorizando funcionalidades relacionadas con el back-end para el desarrollo continuo de nuestro proyecto. Asimismo, 

se identificaron las tareas específicas, se asignaron responsables y se estableció el Sprint Backlog correspondiente, con el fin de asegurar un avance ordenado y colaborativo en el cumplimiento de las metas propuestas.

## 📝 Sprint 3 - Resumen de Planeación

| **Elemento**                        | **Detalle**                                                                                                                       |
|------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|
| 📅 **Fecha**                        | 16-06-2024                                                                                                                        |
| 🕕 **Hora**                         | 18:00 PM                                                                                                                          |
| 📍 **Lugar**                        | Videoconferencia mediante Google Meet                                                                                             |
| 🧾 **Preparado por**                | Jack Roque, Johan Bottger, Gabriel Lapa de la Cruz, Juan Santos, Stanley Gutierrez                                               |
| 👥 **Participantes**                | Jack Roque, Johan Bottger, Gabriel Lapa de la Cruz, Juan Santos, Stanley Gutierrez                                               |
| ✅ **Resumen Sprint 2 Review**      | Desarrollo del frontend con Angular y herramientas clave: Beeceptor (endpoints de prueba), ngx-translate (i18n), Angular Material y Router. |
| 🔁 **Resumen Sprint 2 Retrospective** | Se reconoció que faltaron funcionalidades para completar la experiencia web. Se planteó fortalecer el frontend y mejorar la comunicación y compromiso grupal. |

---

### 🎯 Objetivo del Sprint 3 y User Stories

> Nuestro enfoque está en implementar el backend para autenticación de usuarios, gestión de perfiles de cuidadores y funcionalidad de contacto.  
> Creemos que esto entregará funcionalidades críticas y una mejor experiencia tanto para empresas como usuarios individuales.  
> Esto se confirmará cuando los usuarios puedan registrarse, iniciar sesión, gestionar sus perfiles y visualizar los servicios completados.

---

| **Métrica**               | **Valor** |
|---------------------------|-----------|
| 🔢 **Sprint 3 Velocity**   | 36 SP     |
| 📌 **Sumatoria de Story Points** | 36 SP     |


5.2.3.2. Aspect Leaders and Collaborators

En el Sprint 3 se definieron los siguientes servicios a implementar:

-Authentication Service

-Profile Management Service

-Contact Service

A continuación la matriz de Liderazgo y Colaboración (LACX), donde “L” indica el líder de cada aspecto y “C” a sus colaboradores:

## Asignación de Responsabilidades - Sprint 3 (Backend Services)

| **Miembro del Equipo**              | **Usuario GitHub**     | **User Authentication Service** | **Caregiver Profile Management Service** | **Contact Service** |
|------------------------------------|------------------------|-------------------------------|------------------------------------------|---------------------|
| Santos Torres, Juan Manuel         | JuanManuel312          | C                             | C                                        | C                   |
| Bottger Salazar, Johan Karl        | DeskJobo               | C                             | C                                        | C                   |
| Gutierrez Tume, Stanley Jeremy     | Stan-gt213891          | C                             | **L**                                    | C                   |
| Roque Tello, Jack Eddie            | UPC-Skylar             | C                             | C                                        | **L**               |
| Lapa de la Cruz, Gabriel Omar      | Gabo0722               | **L**                         | C                                        | C                   |

**Leyenda**:  
- **L** = Líder del servicio  
- **C** = Colaborador en el desarrollo del servicio

5.2.3.3. Sprint Backlog 3

El Sprint Backlog 3 está centrado en el desarrollo del back-end de nuestro proyecto. Durante esta etapa, se priorizará el desarrollo de APIs en las siguientes funcionalidades: User Authentication, Caregivers Profile Management, Contact Service.

Se usará Spring Boot con Java como lenguaje base y MySQL como gestor de base de datos.

##  Sprint 3 - Tareas y Progreso

| **User Story ID** | **Título de Historia de Usuario**      | **Task ID** | **Título de Tarea**                     | **Descripción**                                                                                                                    | **Estimación** | **Asignado a**                  | **Estado** |
|-------------------|-----------------------------------------|-------------|------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------|----------------|----------------------------------|------------|
| HU                | Operaciones CRUD                        | 001         | Create                                   | Implementar la operación básica de creación para las tablas de Authentication, Profile Management y Contact Service.              | 3              | Gabriel Lapa de la Cruz          | Done       |
| HU                | Operaciones CRUD                        | 002         | Read                                     | Implementar la operación básica de lectura para las tablas.                                                                       | 2              | Jack Eddie Roque Tello           | Done       |
| HU                | Operaciones CRUD                        | 003         | Update                                   | Implementar la operación básica de actualización para las tablas.                                                                 | 2              | Stanley Gutierrez                | Done       |
| HU                | Operaciones CRUD                        | 004         | Delete                                   | Implementar la operación básica de eliminación para las tablas.                                                                   | 2              | Gabriel Lapa de la Cruz          | Done       |
| HU026             | Integración Backend                     | 005         | Integración                               | Implementar y validar una correcta integración entre el backend y el frontend para todas las funcionalidades.                      | 3              | Jack Eddie Roque Tello           | Done       |
| HU027             | RESTful API users                       | 006         | REST Methods for Agent                   | Implementar métodos para el aggregate `User` que controla la información de los usuarios.                                          | 8              | Juan Santos                      | Done       |
| HU027             | RESTful API users                       | 007         | Command method for User                  | Implementar comandos (`command methods`) para el domain model del bounded context `User`.                                         | 5              | Jack Eddie Roque Tello           | Done       |
| HU028             | RESTful API caregivers profile          | 008         | REST Methods for Caregiver               | Implementar métodos para el aggregate `Caregiver`, controlador del perfil de cuidadores profesionales.                            | 8              | Johan Karls                      | Done       |
| HU028             | RESTful API caregivers profile          | 009         | Command method for Caregiver             | Implementar `CreateCaregiverCommand` para el bounded context `caregivers`.                                                        | 5              | Gabriel Lapa de la Cruz          | Done       |


5.2.3.4. Development Evidence for Sprint Review.

Aquí presentamos nuestra metodología para el diseño y actualización continua del Back-end.

Historial de commits:

##  Evidencia de Commits - Repositorio `MediTecOpen/backend`

| **Repositorio**        | **Branch**  | **Commit ID**                               | **Mensaje de Commit**           | **Descripción Detallada**                                                                                                             | **Fecha**       |
|------------------------|-------------|---------------------------------------------|----------------------------------|---------------------------------------------------------------------------------------------------------------------------------------|-----------------|
| MediTecOpen/backend    | shared      | e0a4fbc55e699d28c6494f6fb0f65c60b7cc535c     | add shared bounded-context       | Implemented the shared bounded-context to centralize common functionality across different parts of the system.                      | 20-06-2025      |
| MediTecOpen/backend    | users       | 025f33527555c5cde11aa932b14756f3579eb0f1     | add application feature          | Added the application feature layer, responsible for handling application logic and workflows.                                       | 20-06-2025      |
| MediTecOpen/backend    | users       | 025f33527555c5cde11aa932b14756f3579eb0f1     | add domain layer                 | Introduced the domain layer to define the core entities, logic, and rules of the users system.                                       | 20-06-2025      |
| MediTecOpen/backend    | users       | d841085ff6565fe8f859319faaeeb3ba93dd5738     | add infrastructure layer         | Implemented the infrastructure layer to manage external dependencies like databases, APIs, and messaging queues.                     | 20-06-2025      |
| MediTecOpen/backend    | users       | 5984fd5697ef2cd4da226f01387b100e12ff90ec     | add interfaces layer             | Added the interfaces layer to define the communication contracts between the system’s different components.                          | 20-06-2025      |
| MediTecOpen/backend    | develop     | 04feb8fa19969b5adfd6a55c26a509afa7371ec8     | Merge pull request #1 from users | Merged the `users` branch into `develop` to integrate the latest features related to user management and functionality.             | 20-06-2025      |
| MediTecOpen/backend    | develop     | e464868aeac4d950330a88759e5077933f4d1449     | Merge pull request #2 from shared| Merged the `shared` branch into `develop` to incorporate the shared bounded-context and standardize common functionality.            | 20-06-2025      |

5.2.3.5. Execution Evidence for Sprint Review.

El tercer sprint alcanzó el objetivo propuesto del desarrollo del backend de la aplicación. Fueron implementadas exitosamente las operaciones CRUD para las funcionalidades Authentication, Caregivers Profile Management y Contact Service, utilizando Spring Boot y MySQL. Cada operación (Create,
 
Read, Update, Delete) fue desarrollada y validada individualmente por los responsables asignados.

5.2.3.6. Services Documentation Evidence for Sprint Review.

Durante este sprint se documentaron los endpoints correspondientes a las funcionalidades desarrolladas: Users Authentication, Caregivers Profile Management y Contact Service. La documentación fue elaborada utilizando OpenAPI (Swagger), permitiendo visualizar las rutas, métodos HTTP, 

parámetros, respuestas esperadas y ejemplos


Caregivers Profile Management Endpoints:

##  Documentación de Endpoints - Caregivers API

| **Endpoint**                    | **Acción Implementada**                    | **Método HTTP** | **Sintaxis de Llamada**              | **Parámetros**                                                                                          |
|--------------------------------|--------------------------------------------|------------------|--------------------------------------|----------------------------------------------------------------------------------------------------------|
| `/caregivers`                  | Obtener todos los cuidadores               | `GET`            | `/api/v1/caregivers`                 | Ninguno                                                                                                   |
| `/caregivers/{id}`             | Obtener cuidador por ID                    | `GET`            | `/api/v1/caregivers/{id}`            | `id` (Path)                                                                                               |
| `/caregivers`                  | Crear cuidador                             | `POST`           | `/api/v1/caregivers`                 | `name`, `age`, `especialty`, `yearsOfExperience`, `location`, `phoneNumber`, `professionalTitle`, `userId` (Body) |
| `/caregivers/{id}`             | Actualizar cuidador                        | `PUT`            | `/api/v1/caregivers/{id}`            | `id` (Path), más los mismos campos del `POST` (Body)                                                      |
| `/caregivers/{id}`             | Eliminar cuidador                          | `DELETE`         | `/api/v1/caregivers/{id}`            | `id` (Path)                                                                                               |
| `/caregivers/specialty`        | Obtener cuidadores por especialidad        | `GET`            | `/api/v1/caregivers/specialty`       | Parámetro `specialty` (Query) - opcional                                                                  |
| `/caregivers/experience`       | Obtener cuidadores por años de experiencia | `GET`            | `/api/v1/caregivers/experience`      | Parámetro `years` (Query) - opcional                                                                      |


Users Authentication Endpoints:

##  Documentación de Endpoints - Users API

| **Endpoint**        | **Acción Implementada**       | **Método HTTP** | **Sintaxis de Llamada**       | **Parámetros**                                                                 |
|---------------------|-------------------------------|------------------|-------------------------------|---------------------------------------------------------------------------------|
| `/users`            | Obtener todos los usuarios    | `GET`            | `/api/v1/users`              | Ninguno                                                                         |
| `/users/{id}`       | Obtener usuario por ID        | `GET`            | `/api/v1/users/{id}`         | `id` (Path)                                                                     |
| `/users`            | Crear usuario                 | `POST`           | `/api/v1/users`              | `firstName`, `email`, `password`, `phone`, `role` (Body)                       |
| `/users/{id}`       | Actualizar usuario            | `PUT`            | `/api/v1/users/{id}`         | `id` (Path), mismos campos del `POST` (Body)                                   |
| `/users/{id}`       | Eliminar usuario              | `DELETE`         | `/api/v1/users/{id}`         | `id` (Path)                                                                     |


5.2.3.7. Software Deployment Evidence for Sprint Review

Durante el Sprint 3 se configuró y desplegó el backend del sistema en un entorno de desarrollo local y en pruebas en la nube. Se creó una base de datos MySQL en un servidor remoto y se configuraron las variables de entorno necesarias para el correcto despliegue del API con Spring Boot.

-Back-end

Pendiente

-Front-end

Pendiente

-Landing Page

https://meditecopen.github.io/LandingPage/

5.2.3.8. Team Collaboration Insights during Sprint.

Durante este Sprint, el equipo trabajó de forma colaborativa para desarrollar las funcionalidades clave del backend. Se realizaron reuniones semanales mediante Google Meet para coordinar tareas y resolver dudas técnicas.


5.3.     Validation Interviews.

En esta sección de Diseño de Entrevistas, se detallan las preguntas diseñadas para recopilar información de los usuarios del sistema CareMe. El objetivo de las entrevistas es validar la propuesta de valor, la funcionalidad y la usabilidad de la plataforma, enfocándose en dos segmentos 

principales: personas que buscan contratar cuidadores por horas y cuidadores profesionales que desean ofrecer sus servicios.

5.3.1.   Diseño de entrevistas.

*Segmento 1: Familiares que buscan contratar cuidadores

¿Qué le ha parecido la idea general de la plataforma CareMe?

¿Cree que esta plataforma podría ayudarle a resolver una necesidad actual o futura?

¿Considera que la plataforma es fácil de entender y usar?

¿Le transmite confianza contratar a través de una aplicación como esta?

¿Le parece útil tener una plataforma digital para encontrar cuidadores?

¿Qué tan cómodo se siente usando tecnología para este tipo de servicios?

¿Ve necesario que este tipo de plataforma exista en el país?

¿Recomendaría esta propuesta a otras personas en su entorno?

*Segmento 2: Cuidadores profesionales

¿Qué opinión le merece la propuesta de la plataforma CareMe?

¿Cree que esta plataforma podría ayudarle a encontrar más oportunidades laborales?

¿Le parece clara y fácil de usar la idea general de la aplicación?

¿Le genera confianza ofrecer sus servicios mediante una plataforma digital?

¿Considera útil contar con un espacio digital donde se reconozca su labor profesional?

¿Qué tan cómodo se siente utilizar tecnología para conectarse con posibles clientes?

¿Cree que esta solución puede mejorar las condiciones del trabajo como cuidador?

¿Recomendaría esta plataforma a otros profesionales del rubro?

5.3.2.   Registro de Entrevistas.

Segmento 1: Personas que necesitan contratar cuidadores por horas para un familiar (Solicitante)
Entrevistado 1: Ushiñahua Becerra, Angela Fabiola

Distrito: Villa el Salvador  / Edad: 24

Entrevistador: Lapa de la Cruz, Gabriel Omar

Link de video: https://youtu.be/HlF42O9C77A

Resumen: Angela observó el recorrido de la aplicación CareMe, pensada para conectar a familias con cuidadores. Ella tiene un familiar con discapacidad y valoró la propuesta como útil y clara. Comentó que actualmente recurre a conocidos o internet para buscar apoyo, pero le preocupa delegar

 el cuidado a personas desconocidas. Considera importante contar con una plataforma segura, fácil de usar y que inspire confianza para encontrar cuidadores responsables.


