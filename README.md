<p align="center">
    <img src="assets/logo/upc.png" alt="upc-logo" width="250px" height="250px"/>
</p>

<h1 align="center">
Universidad Peruana de Ciencias Aplicadas
        </h1>

<h3 align="center">
Carrera: Ingeniería de Software
        <br> <br>
Curso: 1ASI0729 - Desarrollo de Aplicaciones Open Source
    <br> <br>
Sección: 4344
    <br> <br>
Profesor: Rafael Oswaldo Castro Veramendi
    <br> <br>
Ciclo: 2025-01
    <br> <br>
Informe de Trabajo Final
    <br> <br>
Startup: MediTec
        <br> <br>
Producto: CareMe
        </h3>

<div align="center">

| <div style="width:500px">Alumno</div> | <div style="width:150px">Código</div> |
|:-------------------------------------:|:-------------------------------------:|
|        Roque Tello, Jack         |              u20221c448               |
|         Bottger Salazar, Johan          |              u202210735               |
|        Lapa de la Cruz, Gabriel Omar     |              u202216831               |
|        Santos Torres, Juan Manuel        |              u20221a371               |
|        Stanley Gutierrez Tume        |              u202118152               |

</div>

<div align="center"> Abril 2025 </div>

<hr>

## Registro de Versiones del Informe 

| Versión | Fecha | Autor(es) |  Descripción de la modificación   |
| -------- | -------- | -------- | --- |
| TB1     | 21/04/2025     | Todos     | En esta TB1 se desarrollaron todos los puntos del Capítulo I: Introducción, capítulo II: Requirements Elicitation & Analyisis, Capítulo III: Requirements Specification, Capítulo IV: Product UX/UI Design y parte del Capítulo V: Product Implementation, Validation & Deployment. |
| TP1     | 16/05/2025     | Roque Tello, Jack Eddie     | Se aplicaron las correcciones de la retroalimentación en la TB1 y se desarrollo la frontend application, ademas de los siguientes puntos del Capítulo V: Product Implementation, Validation & Deployment (Sprint 2, Sprint Planning2, Aspects Leaders and Collaborators, Sprint Backlog 2, Development Evidence for Sprint Review, Execution Evidence for Sprint Review, Services Documentation Evidence for Sprint Review, Software Deployment Evidence for Sprint Review, Team Collaboration Insights during Sprint, Team Collaboration Insights during Sprint, Avance de Conclusiones, Bibliografía y Anexos)  |
| TB2     | 12/06/2025     | Todos    | Se mejoro la landing page, se agregaron nuevas funcionalidades a la front-end web application y se desarrollaron los siguientes puntos: Sprint 3, Sprint Planning 3, Aspect Leaders and Collaborators, Development Evidence for Sprint Review, Execution Evidence for Sprint Review, Services Documentation Evidence for Sprint Review, Software Deployment Evidence for Sprint Review, Team Collaboration Insights during Sprint, Validation Interviews, Diseño de Entrevistas, Registro de Entrevistas, Evaluaciones según heurísticas, Video About-the-Product.|

# Student Outcome

| Criterio Específico | Acciones realizadas | Conclusiones |
| -------- | -------- | -------- |
| Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería.     | **TB1: Jack Eddie Roque Tello** Realicé presentaciones orales claras y estructuradas sobre los avances del proyecto CareMe. Coordiné algunas reuniones informales para explicar el progreso, las herramientas usadas y los retos técnicos. Intenté comunicarme con mis compañeros para organizar trabajo colaborativo recibiendo respuesta tardía.  **TP1: Jack Eddie Roque Tello** Presenté de forma clara los resultados del desarrollo frontend, integración de la API y la documentación. Respondí consultas y aclaré dudas técnicas a profesores y revisores del proyecto. Mantengo una comunicación profesional con los stakeholders del proyecto, aportando claridad en cada entrega.     | Durante el TB1 y TP1, la comunicación oral fue realizada íntegramente por mi persona, Jack Eddie Roque Tello, debido a la falta de participación de mis compañeros. A pesar de la ausencia de trabajo en equipo, mantuve la objetividad y claridad necesarias para comunicar avances técnicos y administrativos en el proyecto, cumpliendo con los estándares esperados en un entorno profesional de ingeniería.  |

Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería.     |  **TB1: Jack Eddie Roque Tello** Elaboré la documentación técnica y administrativa del proyecto CareMe, incluyendo Lean UX, User Stories, Sprint Planning y backlog. Redacté los antecedentes, problemáticas, perfiles y análisis competitivo con lenguaje técnico claro y accesible. Documenté el desarrollo de la Landing Page con evidencias gráficas y texto explicativo. **TP1: Jack Eddie Roque Tello** Realicé la documentación del desarrollo frontend usando Angular, integración con API, uso de ngx-translate, Angular Material y Router. Elaboré manuales y reportes para las entregas del sprint, incluyendo conclusiones y evidencias de pruebas. Organicé y mantuve actualizado el repositorio de documentación y código.| En ambas entregas, la comunicación escrita fue responsabilidad exclusiva mía, garantizando objetividad, coherencia y claridad. Esta documentación permitió evidenciar el avance del proyecto, facilitar la evaluación y asegurar la trazabilidad de las actividades realizadas, evidenciando compromiso y profesionalismo a nivel individual. |

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

**MediTech** es una startup peruana enfocada en resolver uno de los desafíos más críticos del país: la atención domiciliaria de adultos mayores. Nuestro producto, **CareMe**, nace como respuesta a la falta de plataformas seguras, especializadas y verificadas para este tipo de servicios en el Perú.

Utilizamos tecnologías modernas como algoritmos de emparejamiento, geolocalización y procesamiento de lenguaje natural para conectar familias con cuidadores capacitados. CareMe busca garantizar un cuidado de calidad, seguro y transparente.

**Misión**: Facilitar el acceso a cuidadores certificados mediante una plataforma digital innovadora que mejore la calidad de vida de los adultos mayores.

**Visión**: Ser la plataforma líder en Latinoamérica en servicios de cuidado domiciliario, elevando los estándares de atención mediante tecnología, seguridad y empatía.

### 1.1.2. Perfiles de integrantes del equipo

- **Jack Eddie Roque Tello (U20221C448)**  
  Estudiante de Ingeniería de Software. Cuento con experiencia en JavaScript, C++, Java y Ruby. Me considero proactivo, responsable y con habilidades de comunicación efectiva.

- **Johan Karl Bottger Salazar (U202210735)**  
  Estudiante del séptimo ciclo en Ingeniería de Software. Con conocimientos en C++, Python, JavaScript y HTML. Interesado en metodologías ágiles.

- **Juan Manuel Santos Torres (U20221A371)**  
  Apasionado por el desarrollo de software. Tengo experiencia en JavaScript, Python, Java y C++, y conocimientos en bases de datos y diseño orientado a objetos.

- **Stanley Jeremy Gutierrez Tume (U202118152)**  
  Estudiante en la UPC. En este proyecto, he mejorado la comunicación y habilidades de trabajo en equipo, y estoy motivado por seguir aprendiendo en su carrera.

- **Gabriel Omar Lapa de la Cruz (U202216831)**  
  Estudiante con experiencia en C++, JavaScript y Python. Responsable y enfocado en contribuir al equipo.

---

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

El Perú atraviesa un proceso acelerado de envejecimiento poblacional. En 2023, más de 4.7 millones de peruanos tienen 60 años o más, lo que representa el 13.9% de la población total, y se proyecta que este grupo superará el 20% para 2050 (INEI, 2023). Este fenómeno ha incrementado la demanda

 de servicios de cuidado domiciliario, especialmente en zonas urbanas como Lima, Arequipa y Trujillo, donde también hay una alta concentración de adultos mayores. Según el MINSA (2023), el 66% de los adultos mayores en Lima requiere asistencia diaria para realizar actividades básicas.

Pese a esta creciente necesidad, más del 85% de los servicios de cuidado domiciliario operan de manera informal, sin plataformas digitales confiables ni mecanismos de verificación profesional (CEPLAN, 2023). Las familias suelen contratar cuidadores a través de medios informales como redes 

sociales o recomendaciones personales, lo cual no garantiza seguridad, experiencia ni respaldo. Por otro lado, los cuidadores profesionales carecen de una herramienta formal que les permita ofrecer sus servicios con visibilidad, estabilidad y pagos asegurados.

Este panorama ha generado un mercado riesgoso y desorganizado que afecta a ambas partes: las familias no tienen cómo garantizar el bienestar de sus seres queridos, y los cuidadores enfrentan inestabilidad laboral y falta de reconocimiento. Además, se estima que el mercado informal de 

cuidados mueve alrededor de S/ 450 millones anuales sin control ni regulación, mientras que el 70% de las familias ha tenido dificultades para encontrar cuidadores confiables y el 65% de los cuidadores desea acceder a un canal digital formal para ejercer su labor (GfK Perú, 2023).

Problemática:

What(Qué): ¿Cuál es el problema? 

Existe una carencia de plataformas digitales confiables que conecten a personas que necesitan cuidados domiciliarios con cuidadores profesionales verificados. Esto ha generado un mercado informal e inseguro, donde no hay mecanismos para validar la experiencia, formación o antecedentes del cuidador.

When(Cuándo): ¿Cuándo sucede el problema? 

Este problema es persistente desde hace más de una década, pero se ha intensificado en los últimos 5 años. Según el INEI, en 2023 más de 4.4 millones de peruanos tienen 60 años o más, representando el 13% de la población total, y se proyecta que en 2050 este grupo supere el 20%. La pandemia del COVID-19 también aceleró la demanda de servicios de cuidado en el hogar.

Where(Dónde): ¿Dónde se presenta el problema del negocio?

A nivel nacional, pero con mayor impacto en áreas urbanas. En Lima Metropolitana, por ejemplo, el 66% de los adultos mayores requieren algún tipo de asistencia diaria, según datos del Ministerio de Salud (MINSA). La concentración poblacional y la falta de redes de apoyo formales hacen más agudo el problema en ciudades grandes.

Who (Quienes):

¿Quiénes están involucrados?

Afecta a dos públicos clave:
Familias con miembros dependientes, que no encuentran opciones confiables para cuidados domiciliarios por horas.

Cuidadores profesionales (técnicos en enfermería, egresados de salud) que no cuentan con una plataforma segura, con visibilidad profesional y pagos asegurados.

Why (Por qué):

¿Por qué se origina el problema?

Porque en el Perú más del 85% del mercado de cuidado domiciliario opera de forma informal, sin contratos, sin verificación profesional ni protección legal. Además, solo el 10% de los servicios está mediado por una institución o plataforma formal, según estimaciones del MINSA y estudios privados del sector.

How (Cómo): ¿Cómo afecta este problema?

Las familias recurren a redes informales (Facebook, WhatsApp o recomendaciones), lo que puede resultar en cuidadores sin preparación, con antecedentes no verificados o con disponibilidad inconsistente. Esto expone a los pacientes a riesgos médicos, psicológicos y de seguridad. Al mismo tiempo, los cuidadores no acceden a oportunidades estables ni a condiciones laborales dignas.

How much (Cuánto):

El mercado informal de cuidadores en Perú mueve cerca de S/ 450 millones anuales, pero con alta rotación e informalidad (datos estimados por informes de GfK Perú y entidades de salud privada).
Cerca del 70% de las familias en zonas urbanas han tenido dificultades para encontrar cuidadores confiables, según una encuesta de Pulso Perú (2023).
El 65% de los cuidadores entrevistados informalmente desea un canal digital formal para ofrecer sus servicios con seguridad y respaldo.



---

## 1.2.2. Lean UX Process

### 1.2.2.1. Lean UX Problem Statements

En el Perú, muchas personas que requieren cuidados especiales, como adultos mayores o personas con discapacidad, enfrentan dificultades para encontrar cuidadores profesionales de confianza, disponibles por horas, y adecuados a sus necesidades específicas. Esta situación se agrava por la 

informalidad en la contratación, la falta de canales seguros y accesibles, y el desconocimiento sobre la oferta existente de profesionales capacitados. Por otro lado, muchos egresados de carreras del sector salud están dispuestos a brindar estos servicios pero carecen de una plataforma 

formal que los conecte directamente con quienes lo necesitan.

Ante esta situación, surge nuestra pregunta de negocio:

 ¿Cómo podemos facilitar la conexión entre personas que requieren servicios de cuidado y profesionales capacitados, de manera segura, accesible y confiable?


---

### 1.2.2.2. Lean UX Assumptions

Business Assumptions

Existencia de demanda: Suponemos que hay una cantidad significativa de personas que requieren servicios de cuidado por horas y buscan una alternativa confiable y segura.

Interés de los cuidadores: Suponemos que existe un grupo considerable de egresados del sector salud interesados en generar ingresos a través del cuidado por horas.

Sostenibilidad del modelo: Suponemos que el modelo de comisiones por servicio y suscripciones premium para cuidadores permitirá mantener y escalar la plataforma.

Business Outcomes

Generación de ingresos sostenibles mediante comisiones por cada servicio concretado y planes de suscripción para cuidadores.


Crecimiento de la comunidad, tanto de usuarios que requieren cuidados como de cuidadores registrados y activos.


Reconocimiento de marca como plataforma segura, profesional y socialmente responsable en el ámbito de cuidados personales.


User Benefits

Acceso a cuidadores calificados, de forma rápida y segura, para quienes necesitan servicios de cuidado.


Oportunidades de ingreso para cuidadores profesionales o en formación, que podrán ofrecer sus servicios con flexibilidad horaria.


Seguridad y confianza, gracias a mecanismos de verificación, valoraciones y soporte dentro de la plataforma.


### 1.2.2.3. Lean UX Hypothesis Statements

-Creemos que, si conectamos a familias con cuidadores certificados a través de una app segura y especializada, sabremos que hemos tenido éxito cuando al menos el 30% de los usuarios que normalmente contratan cuidadores informalmente usen la plataforma durante los primeros 3 meses posteriores a su lanzamiento.

-Creemos que, si ofrecemos verificación de credenciales y calificaciones públicas, sabremos que hemos tenido éxito cuando al menos el 80% de los usuarios reporten sentirse más seguros al contratar cuidadores, según encuestas realizadas durante los primeros 6 meses.

-Creemos que, si permitimos a los cuidadores gestionar su agenda y pagos desde la app, sabremos que hemos tenido éxito cuando al menos el 50% de ellos usen la plataforma de forma recurrente dentro de los primeros 6 meses de vida de la aplicación..

---

### 1.2.2.4. Lean UX Canvas

**Problema de negocio:**  
Falta de plataformas digitales que formalicen el mercado de cuidado por horas.

**Ideas de solución:**  
- App web y móvil con filtros inteligentes y geolocalización.  
- Verificación de credenciales, pagos seguros y soporte.  
- Recordatorios, botón de emergencia y calificaciones.

**Resultados esperados:**  
- 1000 contrataciones en los primeros 6 meses.  
- 500 cuidadores registrados.  
- Ingresos sostenibles por comisiones.

**Usuarios:**  
- Familias con adultos mayores o personas en recuperación.  
- Cuidadores profesionales o egresados del área de salud.

**Validaciones necesarias:**  
- Disposición de familias a usar apps para contratar cuidadores.  
- Interés de cuidadores en ofrecer servicios a través de la app.

---

## 1.3. Segmentos Objetivo

Segmento objetivo 1: Personas que necesitan contratar cuidadores por horas para un familiar.

-Familiares de personas mayores o dependientes que requieren asistencia por horas (aseo, alimentación, compañía, etc)

-Personas con familiares en recuperación post-operatoria o con condiciones temporales de salud

-Profesionales ocupados que no pueden atender directamente a sus seres queridos en ciertos horarios 

*Aspectos demográficos:

-Sexo: Masculino y femenino

-Edades: Adultos entre 20 y 65 años

-Nivel socioeconómico: Clases B y C (media alta y media)

-Aspectos geográficos:

-Nacionalidad: Peruana

-Zona geográfica de residencia: Urbana

-Departamento: Principalmente Lima Metropolitana

*Aspectos psicográficos:

-Valoran la seguridad y bienestar de sus familiares

-Buscan soluciones prácticas y confiables debido a la falta de tiempo

-Tienden a desconfiar de redes informales y prefieren plataformas verificadas

-Son usuarios de tecnología móvil (apps, redes sociales)

-Están dispuestos a pagar por servicios profesionales si sienten respaldo, seguimiento y Calidad

Segmento objetivo 2: Personas que ofrecen su tiempo y conocimientos para cuidar a otros por horas, a cambio de una retribución económica. 

-Egresados de carrera de salud (Enfermería, Técnicas en enfermería, Medicina, Terapia Física)

-Cuidadores independientes con experiencia previa

*Aspectos demográficos:

-Sexo: Masculino y femenino

-Edades: Adultos entre 30y 65 años

-Nivel socioeconómico: Clases C y D (media y media baja)

-Ocupación: Técnicos en enfermería, cuidadores con experiencia previa, fisioterapeutas, egresados de medicina o terapia

*Aspectos geográficos:

-Nacionalidad: Peruana

-Zona geográfica de residencia: Zonas urbanas y semiurbanas

-Departamento: Principalmente Lima Metropolitana

*Aspectos psicográficos:

-Buscan generar ingresos con flexibilidad horaria

-Desean oportunidades formales y estables de trabajo

-Valoran la reputación, calificaciones y visibilidad profesional

-Suelen usar redes sociales y smartphones para conectarse con potenciales clientes

-Están dispuestos a capacitarse o certificar sus conocimientos si eso les permite acceder a más y mejores oportunidades


---


