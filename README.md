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

- Buscar

- Inicio

- Usuario

-Chat

- Calendario

-Pagos

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
 
[![diagramas.png](https://i.postimg.cc/VsdhS0mW/diagramas.png)](https://postimg.cc/PNny9xLC)

Segmento objetivo: Solicitantes y Cuidadores 

User goal: Como solicitante, quiero tener la capacidad de encontrar y seleccionar fácilmente a los cuidadores más adecuados para las necesidades de mi familiar.

Descripción: En el siguiente wireframe se muestra los pasos que debe seguir para encontrar un 

[![serach.png](https://i.postimg.cc/L51vxfsd/serach.png)](https://postimg.cc/303gRkp9)

User goal: Como solicitante o cuidador, deseo poder iniciar una conversación con un cuidador específico después de verlo en la lista de búsqueda o en su perfil.

Descripción: Se le muestra la pestaña de mensajes que tienen entre ellos tanto cuidador como solicitante.

[![mensajes.png](https://i.postimg.cc/Df9x8CC7/mensajes.png)](https://postimg.cc/QVqQzqGz)


User goal:Como usuario de la plataforma (tanto solicitante como cuidador), quiero tener la capacidad de gestionar de forma segura y transparente los pagos y las transacciones relacionadas con los servicios de cuidado.

Descripción:Se le muestra la configuración de pago , historial,métodos de retiro.

4.5. Web Applications Prototyping.

Una style guideline  es un conjunto de reglas y pautas que establecen la forma en que deben redactarse, diseñarse o presentarse documentos, contenido web, software u otros tipos de trabajos creativos.

A continuación, se especificarán los parámetros implementados en la estructura del proyecto. En particular, se detallarán los principales criterios tomados en cuenta para las decisiones de interacción —como los elementos de la interfaz y los principios aplicados a ellos— relacionados con la 

Arquitectura de Información de nuestra aplicación en las plataformas iOS y Android.

4.6. Domain-Driven Software Architecture.
4.6.1. Software Architecture Container Diagrams.

[![containers.png](https://i.postimg.cc/TP1Vkmkk/containers.png)](https://postimg.cc/d7MZ37cd)


4.6.2. Software Architecture Components Diagrams.

[![diagrmas.png](https://i.postimg.cc/C5TbL2wt/diagrmas.png)](https://postimg.cc/k6s2Tf6F)

4.7. Software Object-Oriented Design.
4.7.1. Class Diagrams.

[![class-deaf.png](https://i.postimg.cc/vZHfBfdQ/class-deaf.png)](https://postimg.cc/qzSzDtRY)

4.7.2. Class Dictionary.

Clase: usuario

Descripción: Clase base que representa a cualquier usuario de la plataforma.

Atributos:

id: String – Identificador único del usuario.

nombre: String – Nombre completo del usuario.

correo: String – Correo electrónico.

contraseña: String – Contraseña cifrada.

teléfono: String – Número de contacto.

rol: String – Rol del usuario (Solicitante o Cuidador).

* Clase: Solicitante (hereda de Usuario)

Descripción: Usuario que contrata servicios de cuidado.

Atributos:

dirección: String – Dirección de domicilio.

historial Servicios: List<Servicio> – Lista de servicios contratados.

metodoPago: MetodoPago – Método de pago asociado.

Métodos:

agendarServicio() – Programa un nuevo servicio.

cancelarServicio() – Cancela un servicio agendado.

* Clase: Cuidador (hereda de Usuario)

Descripción: Profesional de salud que brinda servicios a través de la plataforma.

Atributos:

especialidad: String – Especialización médica o técnica.

experiencia: Int – Años de experiencia.

disponibilidad: String – Días y horarios disponibles.

certificaciones: List<String> – Certificados y validaciones.

calificaciones: List<Reseña> – Valoraciones recibidas.

Métodos:

aceptarServicio() – Acepta una solicitud de servicio.

completarServicio() – Marca un servicio como completado.

* Clase: Servicio

Descripción: Representa una sesión de cuidado entre un solicitante y un cuidador.

Atributos:

id: String – Identificador del servicio.

fecha: Date – Fecha del servicio.

duracionHoras: Int – Duración en horas.

estado: String – Estado del servicio (pendiente, en curso, completado).

solicitante: Solicitante – Usuario que contrata.

cuidador: Cuidador – Profesional que ofrece el servicio.

Métodos:

iniciar() – Cambia el estado del servicio a "en curso".

finalizar() – Finaliza el servicio.

* Clase: MetodoPago

Descripción: Representa un método de pago registrado por el usuario.

Atributos:

tipo: String – Tipo (tarjeta, transferencia, etc.).

datos: String – Información codificada o token del método.

Métodos:

procesarPago() – Realiza la operación de pago.

* Clase: Pago
Descripción: Transacción financiera generada por un servicio.

Atributos:

id: String – ID único del pago.

monto: Float – Valor a pagar.

estado: String – Estado del pago (pendiente, procesado).

metodo: MetodoPago – Método utilizado.

Métodos:

generarRecibo() – Emite un comprobante de pago.

*Clase: Reseña
Descripción: Valoración emitida por el solicitante al finalizar un servicio.

Atributos:

puntuacion: Int – Puntuación del 1 al 5.

comentario: String – Opinión escrita.

autor: Solicitante – Usuario que emite la reseña.

Métodos:

mostrar() – Muestra la reseña.

*Clase: Mensaje
Descripción: Mensaje enviado entre usuarios a través del sistema de mensajería.

Atributos:

contenido: String – Texto del mensaje.

fecha: Date – Fecha y hora de envío.

emisor: Usuario – Usuario que envió el mensaje.

receptor: Usuario – Usuario que lo recibió.

* Clase: Notificacion

Descripción: Notificación enviada a los usuarios por eventos importantes.

Atributos:

titulo: String – Título de la notificación.

mensaje: String – Contenido del mensaje.

destinatario: Usuario – Usuario que la recibe.

Métodos:

enviar() – Envía la notificación al destinatario.

4.8. Database Design.
4.8.1. Database Diagram.

[![database.png](https://i.postimg.cc/65z4Dq4F/database.png)](https://postimg.cc/MvMGBWDY)

ENTIDADES:

* Usuarios

Esta entidad representa a las personas que utilizan el sistema. Un usuario puede ser un solicitante, un cuidador, o tener otro rol dentro del sistema.

id: Identificador único del usuario (clave primaria).

nombre: Nombre completo del usuario.

correo: Dirección de correo electrónico del usuario.

contraseña: Contraseña de acceso para autenticar al usuario.

telefono: Número de teléfono del usuario.

rol: Define el tipo de usuario (por ejemplo, "solicitante" o "cuidador").

* Solicitantes

Los solicitantes son los usuarios que piden servicios a los cuidadores. Esta entidad almacena información sobre los solicitantes y sus métodos de pago.

id_usuario: Referencia al id del usuario (clave foránea).

direccion: Dirección de residencia del solicitante.

metodo_pago_id: Identificador del método de pago utilizado por el solicitante.

* Cuidadores

Los cuidadores son los usuarios que prestan los servicios solicitados. Esta entidad almacena información sobre sus especialidades, experiencia y disponibilidad.

id_usuario: Referencia al id del usuario (clave foránea).

especialidad: Área en la que el cuidador está especializado.

experiencia: Años de experiencia del cuidador.

disponibilidad: Horarios en los que el cuidador está disponible para ofrecer servicios.

* Servicios

Esta entidad representa los servicios solicitados por los solicitantes y prestados por los cuidadores. Los servicios incluyen detalles sobre la fecha, estado y duración.

id: Identificador único del servicio (clave primaria).

solicitante_id: Referencia al solicitante que hizo la solicitud.

cuidador_id: Referencia al cuidador que ofrece el servicio.

fecha: Fecha en la que se realiza el servicio.

estado: Estado del servicio (por ejemplo, "pendiente", "completado").

duracion_horas: Duración del servicio en horas.

* Pagos

Los pagos representan las transacciones realizadas para los servicios prestados. Esta entidad incluye detalles sobre el monto, el tipo de pago y el estado.

id: Identificador único del pago (clave primaria).

servicio_id: Referencia al servicio asociado con este pago.

monto: Monto total del pago.

tipo_pago: Tipo de pago (por ejemplo, "tarjeta de crédito", "efectivo").

estado: Estado del pago (por ejemplo, "completado", "pendiente").

* Reseñas

Las reseñas son opiniones que los solicitantes pueden dejar sobre los servicios que recibieron de los cuidadores. Cada reseña tiene una puntuación y un comentario.

id: Identificador único de la reseña (clave primaria).

servicio_id: Referencia al servicio sobre el cual se deja la reseña.

puntuación: Puntuación dada al servicio (por ejemplo, del 1 al 5).

comentario: Comentario dejado por el solicitante sobre el servicio.

* Certificaciones

Los cuidadores pueden tener certificaciones que validan su experiencia o habilidades en ciertas áreas. Esta entidad almacena los detalles de estas certificaciones.

id: Identificador único de la certificación (clave primaria).

cuidador_id: Referencia al cuidador que posee la certificación.

documento: Enlace o nombre del documento que certifica al cuidador.

Institución: Institución que otorga la certificación.

estado: Estado de la certificación (por ejemplo, "válida", "expirada").

*Mensajes

Los mensajes permiten la comunicación entre los usuarios del sistema (solicitantes, cuidadores, etc.). Esta entidad guarda el contenido de los mensajes enviados entre los usuarios.

id: Identificador único del mensaje (clave primaria).

emisor_id: Referencia al usuario que envía el mensaje.

receptor_id: Referencia al usuario que recibe el mensaje.

contenido: Contenido del mensaje.

fecha: Fecha y hora de envío del mensaje.

* Notificaciones

Las notificaciones informan a los usuarios sobre eventos importantes en el sistema, como la aceptación de un servicio o un nuevo mensaje. Esta entidad almacena los detalles de esas notificaciones.

id: Identificador único de la notificación (clave primaria).

usuario_id: Referencia al usuario que recibe la notificación.

Título: Título de la notificación.

mensaje: Contenido de la notificación.

fecha: Fecha y hora en que se genera la notificación.

leído: Indicador de si el usuario ha leído la notificación (valor booleano).

Cada entidad tiene una función específica dentro del sistema, y las relaciones entre ellas se dan a través de claves foráneas (FK). Estas claves foráneas permiten conectar a un solicitante con sus servicios, a un cuidador con sus servicios y pagos, y mucho más. Las flechas en el diagrama muestra cómo se interrelacionan estas entidades.

