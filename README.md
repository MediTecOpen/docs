# CAPÍTULO IV. PRODUCT UX/UI DESIGN
## 4.1. Style Guidelines.

Un Style Guideline constituye un conjunto de normas y directrices destinadas a estandarizar la redacción, el diseño y la presentación de documentos, contenidos digitales, desarrollos de software u otros productos creativos. A continuación, se detallan las especificaciones correspondientes a los parámetros adoptados en la estructura del proyecto.

 4.1.1. General Style Guidelines.

Brand Overview
CareMe es una plataforma digital innovadora que conecta a familias con cuidadores profesionales certificados. Su diseño visual busca transmitir confianza, profesionalismo y calidez, pilares fundamentales en la atención domiciliaria de adultos mayores.

Brand Name
El nombre "CareMe" combina el concepto de cuidado (“Care”) con el pronombre “Me” para enfatizar la atención personalizada y humana que brinda la plataforma. Reforzamos la empatía y el trato digno a través del nombre y su identidad visual.

Typography
 Para mantener una experiencia accesible y amigable, se usarán tipografías modernas y legibles como:

Headings: Montserrat Bold

Body text: Open Sans Regular

Buttons: Open Sans Semibold

Links: Open Sans Italic

Colors:

| **Color**         | **Código HEX** | **Significado**                              |
|-------------------|----------------|----------------------------------------------|
| Azul Profesional  | `#1A73E8`      | Confianza, tecnología, seguridad              |
| Verde Cálido      | `#4CAF50`      | Cuidado, bienestar, empatía                   |
| Blanco            | `#FFFFFF`      | Claridad, limpieza, accesibilidad             |
| Gris Neutro       | `#E0E0E0`      | Neutralidad, profesionalismo                  |
| Negro             | `#212121`      | Seriedad, lectura clara                       |


4.1.2. Web Style Guidelines.

La plataforma será completamente responsive, adaptándose a móviles, tablets y escritorios. Se seguirá el patrón de lectura en Z para guiar la mirada del usuario desde el logo, pasando por el menú y terminando en los llamados a la acción.

El diseño prioriza una experiencia accesible, con contraste visual suficiente, botones grandes y etiquetas claras. El estilo también comunicará calidez y profesionalismo, elementos clave para este tipo de servicio.

4.2. Information Architecture.

En esta sección se describe cómo se estructura la información dentro de la plataforma CareMe, considerando la experiencia tanto en la Landing Page como en la Aplicación Web para contratantes y cuidadores. El objetivo es asegurar una navegación fluida, comprensible y eficiente, maximizando la

 usabilidad y minimizando el esfuerzo cognitivo del usuario.

La arquitectura se apoya en principios de organización jerárquica, sistemas de etiquetado claros, mecanismos de búsqueda efectivos y patrones de navegación intuitivos, diseñados para atender a dos perfiles principales: Contratante (familiares que buscan cuidados por horas) y Cuidador 

(profesionales de la salud certificados).

4.2.1. Organization Systems.

Tipo de organización usada:

 Se ha optado por una estructura jerárquica combinada con organización por tareas y roles, lo cual facilita que cada tipo de usuario (contratante o cuidador) pueda encontrar fácilmente la funcionalidad que necesita según su objetivo y etapa dentro del proceso (registro, búsqueda, 

agendamiento, comunicación, pagos, etc.).

Organización de la Landing Page:

*Encabezado (Header): Logo, menú principal (Inicio, Servicios, Cómo Funciona, Preguntas Frecuentes, Contacto) y botones de acción (Iniciar Sesión / Registrarse).


*Sección Introductoria (Hero): Mensaje de valor claro ("Conecta con cuidadores de confianza desde casa"), imagen empática (persona mayor + cuidador), botón CTA principal (“Buscar cuidadores”).


*Beneficios: Lista ilustrada de beneficios (“Atención validada”, “Pagos seguros”, “Cuidadores certificados”).


*Cómo Funciona: Explicación paso a paso (Buscar → Agendar → Confirmar → Valorar).


*Testimonios / Opiniones: Opiniones reales de familias usuarias de la plataforma.


*Pie de Página (Footer): Enlaces legales, datos de contacto, redes sociales, derechos de autor.


*Organización de la Aplicación Web (por rol)

-Contratante

*Inicio: Vista general con acceso rápido a cuidadores destacados, próximos servicios agendados, y mensajes recientes.


*Buscar cuidadores: Filtros por especialidad, horario, zona, experiencia.


*Mi Perfil: Editar datos, métodos de pago, preferencias.


*Mis Servicios: Ver servicios pasados, activos y futuros.


*Mensajes: Bandeja de conversación con cuidadores.


*Centro de Ayuda: FAQs, contacto con soporte.


-Cuidador

*Inicio: Resumen de próximos servicios, notificaciones nuevas.


*Solicitudes recibidas: Panel para aceptar o rechazar servicios.


*Mi Perfil Profesional: Descripción, certificaciones, disponibilidad.


*Historial: Servicios completados y valoraciones recibidas.


*Configuración de pagos: Métodos de retiro, historial de ingresos.


*Soporte: Chat en vivo o por correo, preguntas frecuentes.


4.2.2. Labeling Systems.

Los sistemas de etiquetado usados en CareMe tienen como objetivo lograr una interfaz clara, coherente y accesible para usuarios de todas las edades, en especial personas adultas que podrían tener menor familiaridad con herramientas digitales.

Tipos de etiquetas utilizadas:

1. Etiquetas Textuales (Text Labels):

Acción directa y sencilla: Usamos verbos claros y en imperativo, como: “Buscar cuidador”, “Agendar servicio”, “Confirmar asistencia”, “Ver historial”.

Consistencia en las vistas: Las secciones principales conservan la misma nomenclatura en el menú, breadcrumbs y botones.

Ejemplos:

-“Mis Servicios”

-“Mi Perfil”

-“Solicitudes Recibidas”

-“Confirmar Asistencia”

-“Historial de Servicios”

-“Configuración de pagos”

2. Etiquetas de Encabezado (Headings):

Se utilizan para estructurar jerárquicamente el contenido dentro de cada vista:

-H1: Título de la vista principal (ej. "Buscar Cuidadores")

-H2: Subsecciones o acciones importantes (ej. "Filtros", "Resultados de búsqueda")

-H3-H4: Etiquetas menores dentro de tarjetas, formularios, etc.

3. Etiquetas Icónicas (Iconic Labels):

Incorporamos íconos simples y reconocibles junto al texto o de forma independiente para:

-🔍 Buscar

-🏠 Inicio

-👤 Usuario

-💬 Chat

-📅 Calendario

-💳 Pagos

4. Etiquetas Contextuales / Tooltips:

Se mostrarán mensajes flotantes al pasar el cursor sobre íconos o botones complejos (ej. “Ver más detalles del cuidador”, “Método de pago no configurado”).

4.2.3. SEO Tags and Meta Tags

La optimización para motores de búsqueda es fundamental para posicionar CareMe como una plataforma de confianza y relevante en el sector de salud y servicios domiciliarios. Usaremos etiquetas SEO básicas y meta tags para asegurar una correcta indexación y visualización en los resultados de búsqueda.

<!-- Título de la plataforma -->

<title>CareMe - Cuidadores certificados a domicilio</title>

<!-- Descripción corta para buscadores -->

<meta name="description" content="CareMe es la plataforma digital que conecta a familias con cuidadores profesionales certificados en Perú. Servicios confiables, seguros y personalizados.">

<!-- Keywords principales -->

<meta name="keywords" content="cuidadores a domicilio, atención adultos mayores, servicios por horas, salud, cuidado, enfermería, cuidado postoperatorio, Lima, Perú">

<!-- Configuración responsive -->

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<!-- Autoría y derechos -->

<meta name="author" content="MediTech - CareMe">

<meta name="copyright" content="© 2024 MediTech. Todos los derechos reservados">

4.2.4. Searching Systems. 

El sistema de búsqueda de CareMe es uno de los ejes centrales de la experiencia del usuario contratante. Se han diseñado múltiples formas para facilitar el descubrimiento de cuidadores de manera rápida, intuitiva y efectiva:

1. Búsqueda por dirección o zona

Campo de texto donde el usuario puede ingresar la dirección (ej. "Av. Javier Prado 456") o el distrito (ej. "San Borja").

El sistema sugiere zonas conforme se escribe (autocompletado).

Los resultados se muestran en orden de cercanía geográfica.

2. Búsqueda por ubicación actual (geolocalización)

Permite al usuario utilizar su ubicación en tiempo real para encontrar cuidadores cercanos.

Ideal para quienes necesitan atención urgente o inmediata en su entorno.

3. Filtros avanzados

Por tipo de servicio: Cuidado postoperatorio, acompañamiento, alimentación, baño.

Por experiencia profesional: años de experiencia, tipo de certificación.

Por disponibilidad horaria: turnos mañana, tarde o noche.

Por género del cuidador (opcional).

Por valoraciones de otros usuarios (ranking de estrellas).

4. Mapa interactivo (map view)

Integración con APIs de mapas (Google Maps u OpenStreetMap).

Visualización de la ubicación de cada cuidador con pines interactivos.

Al hacer clic sobre un pin, se abre una tarjeta con perfil resumido, disponibilidad y botón para agendar.

5. Búsqueda por nombre de cuidador (si el usuario ya tiene a alguien en mente)

Campo de búsqueda por nombre/apellido.

Útil para usuarios recurrentes o recomendaciones externas.

4.2.5. Navigation Systems.

Menú fijo con navegación vertical u horizontal según el dispositivo. Las vistas cambiarán según el rol del usuario (Contratante o Cuidador). La experiencia será intuitiva, con flujos naturales desde el registro hasta la contratación.

4.3. Landing Page UI Design.

4.3.1. Landing Page Wireframe.

![Imagen de Diseño Visual](https://i.imgur.com/riTZJNS.png)

4.3.2. Landing Page Mock-up.

![Mockup de CareMe](https://i.imgur.com/TtFuksq.png)


4.4. Web Applications UX/UI Design.
4.4.1. Web Applications Wireframes.
4.4.2. Web Applications Wireflow Diagrams.

Link Figma: https://www.figma.com/design/zGaYnTarmHelTTlLmd3mZy/Untitled?node-id=0-1&t=3r5bAlEjcx2TmOLR-1 

![Imagen de Diseño Visual](https://i.imgur.com/riTZJNS.png)

![Pantalla de Registro - CareMe](https://i.imgur.com/cLqFrs5.png)

![Pantalla de Inicio de Sesión - CareMe](https://i.imgur.com/cpc8gF8.png)

![Mockup 2 - CareMe](https://i.imgur.com/JwlyEtm.png)

![Vista del Servicio - CareMe](https://i.imgur.com/I0N7tTB.png)

![Vista de Perfil Solicitante - CareMe](https://i.imgur.com/nK1ociE.png)

![Vista de Perfil Cuidador - CareMe](https://i.imgur.com/HHFZlZv.png)

4.4.2. Web Applications Mock-ups.

![Mockup - Pantalla Adicional de CareMe](https://i.imgur.com/qLaD55w.png)

![Mockup final - CareMe](https://i.imgur.com/vRXUZOX.png)

![Mockup final 4 - CareMe](https://i.imgur.com/BPd3qp2.png)

![Mockup final 5 - CareMe](https://i.imgur.com/Dw4HCcZ.png)

![Mockup final 6 - CareMe](https://i.imgur.com/1kxCNzd.png)

![Pantalla de Pago - CareMe](https://i.imgur.com/YE3bzvb.png)

4.4.3. Web Applications User Flow Diagrams.
 




