# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

## To-Be Scenario Map – Segmento 1: Persona que busca un cuidador

| Phases                      | Doing                                                                                                                                                  | Thinking                                                                                              | Feeling                                                                                         |
|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| Búsqueda del cuidador      | Uso CareMe para encontrar cuidadores cercanos filtrados por especialización (ej. demencia, post-operatorio). La app me muestra perfiles con puntajes y reseñas verificadas. | “Qué bueno encontrar opciones cerca y con buenas reseñas”.<br>“Me gusta que puedo filtrar por necesidades específicas” | Me siento aliviado al ahorrar tiempo y confianza en los perfiles autorizados.                  |
| Validación y selección     | Veo certificaciones validadas por la plataforma (antecedentes policiales, cursos). Puedo comparar opciones y precios transparentes, también tengo un chat integrado para coordinar detalles. | “Es seguro porque la app ya verificó sus credenciales”.<br>“Las valoraciones me ayudan a decidir”   | Me da tranquilidad la validación automática y satisfacción al elegir cuidadores con información clara. |
| Contratación               | Cuento con un contrato digital con los términos claros. Realizo el pago de forma segura desde la app y recibo mi comprobante. Me llegan alertas recordatorias. | “Es práctico hacer todo el proceso de pago desde la app”                                             | Siento seguridad con los contratos y pagos rastreables.                                         |
| Seguimiento Post-servicio | Recibo un registro diario del cuidador (horas, actividades) y reportes semanales del progreso. Puedo calificar el servicio.                                | “Ahora veo el historial de cuidados”.<br>“Puedo ajustar el servicio según los reportes”              | Siento empoderamiento al tener el control.<br>Me da motivación al ver progresos y paz mental.  |

---

## To-Be Scenario Map – Segmento 2: Persona que ofrece servicios de cuidado

| Phases                             | Doing                                                                                                                                                       | Thinking                                                                                                               | Feeling                                                                                                 |
|-----------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------|
| Buscar personas que requieran de un cuidador | Uso CareMe para crear un perfil público con mi disponibilidad, especialización y zona de cobertura. La app muestra mi perfil a familias cercanas.            | “Antes perdía horas publicando en redes. Ahora las familias me encuentran directamente.”                              | Me da tranquilidad al saber que mi perfil está visible para quienes realmente necesitan mis servicios. |
| Demostrar mi experiencia y certificaciones  | Subo mis certificados a CareMe, que son verificados por instituciones aliadas. Mi perfil muestra un sello de ‘Profesional Certificado’.                    | “Las familias confían porque ven mis credenciales validadas. No tengo que convencerlas con palabras.”                | Me da seguridad al saber que mi trabajo está respaldado por una plataforma seria.                      |
| Ofrecer servicios especializados           | Me uno a una red de cuidadores especializados. La app me asigna casos según mi expertise.                                                                  | “Antes me sentía limitado para atender casos complejos. Ahora colaboro con otros y accedo a capacitaciones.”         | Siento empoderamiento al ampliar mi oferta de servicios y aprender de una comunidad especializada.     |
| Recibir reseñas y compartirlas            | Después de cada servicio, las familias me califican. Las reseñas se publican automáticamente y puedo compartirlas.                                         | “Mis esfuerzos se reflejan en mi reputación digital. Las nuevas familias contratan en base a testimonios reales.”    | Siento orgullo al ver cómo mi trabajo impacta positivamente y atrae más oportunidades.                |

## Épicas del Proyecto – CareMe

| EPIC ID  | Título                                      | Descripción                                                                                                                                                   |
|----------|---------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| EP-001   | Búsqueda y descubrimiento de cuidadores e iniciar sesión | Como contratante (familiar que busca cuidado), quiero tener la capacidad de encontrar y seleccionar fácilmente a los cuidadores más adecuados para las necesidades de mi familiar. |
| EP-002   | Gestión de Perfiles de Usuarios              | Como usuario de la plataforma (tanto solicitante como cuidador), quiero tener la capacidad de crear, ver y editar mi perfil para proporcionar y acceder a la información necesaria para utilizar CareMe de manera efectiva y segura. |
| EP-003   | Comunicación entre usuarios y cuidadores     | Como usuario de la plataforma (tanto solicitante como cuidador), quiero tener la capacidad de solicitar, aceptar, programar y gestionar los servicios de cuidado de manera eficiente. |
| EP-004   | Comunicación entre Usuarios                  | Como usuario de la plataforma (tanto solicitante como cuidador), quiero tener la capacidad de comunicarse directamente con la otra parte para aclarar detalles, coordinar la logística del servicio y resolver cualquier duda o problema que pueda surgir. |
| EP-005   | Gestión de Pagos y Transacciones             | Como usuario de la plataforma (tanto solicitante como cuidador), quiero tener la capacidad de gestionar de forma segura y transparente los pagos y las transacciones relacionadas con los servicios de cuidado. |
| EP-006   | Soporte y Ayuda                              | Como usuario de la plataforma (tanto solicitante como cuidador), quiero tener acceso a recursos de ayuda y soporte para resolver dudas, solucionar problemas y obtener asistencia en el uso de CareMe. |

---

## 3.2. User Stories
## Historias de Usuario – CareMe

| User Story ID | Título                                                    | Descripción                                                                                                                                                 |
|---------------|-----------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| HU-001        | Iniciar sesión en Care me                                 | Como usuario quiero poder ingresar a Care me para poder acceder a todas sus funcionalidades                                                                |
| HU-002        | Buscar cuidadores ingresando dirección                    | Como solicitante, quiero buscar cuidadores ingresando una dirección específica para encontrar opciones cercanas a mi domicilio.                            |
| HU-003        | Ajustar radio de búsqueda                                 | Como solicitante, quiero poder ajustar el radio de búsqueda para ampliar o reducir el área de cobertura.                                                   |
| HU-004        | Mostrar estado de actividad del cuidador                  | Como solicitante, quiero ver claramente si un cuidador está actualmente activo o no en la plataforma.                                                      |
| HU-005        | Buscar cuidadores usando mi ubicación actual              | Como solicitante, quiero buscar cuidadores utilizando la ubicación actual de mi dispositivo para encontrar opciones cercanas a donde me encuentro.         |
| HU-006        | Acceder a la página de registro de solicitante           | Como nuevo usuario, quiero acceder a una página específica para registrarme como solicitante.                                                              |
| HU-007        | Registrarse como solicitante proporcionando información básica | Como nuevo usuario, quiero registrarme como solicitante proporcionando mi nombre, correo electrónico y número de teléfono, y estableciendo una contraseña. |
| HU-008        | Ver mi perfil                                              | Como solicitante registrado, quiero poder acceder a la sección de mi perfil para revisar la información que he proporcionado.                              |
| HU-009        | Cancelar un servicio programado                           | Como solicitante, quiero poder cancelar un servicio de cuidado programado en caso de necesidad, siguiendo las políticas de cancelación.                     |
| HU-010        | Ver el historial de servicios completados                 | Como solicitante, quiero poder ver un registro de los servicios de cuidado que ya se han completado.                                                       |
| HU-011        | Confirmar asistencia a un servicio programado             | Como cuidador, quiero poder confirmar mi asistencia a un servicio de cuidado programado antes de la fecha y hora de inicio.                                |
| HU-012        | Marcar un servicio como completado                        | Como cuidador, quiero poder marcar un servicio de cuidado como completado una vez que lo haya finalizado.                                                  |
| HU-013        | Iniciar conversación                                      | Como solicitante o cuidador, quiero poder iniciar una conversación con un cuidador específico después de verlo en la lista de búsqueda o en su perfil.     |
| HU-014        | Recibir notificación de nuevo mensaje del cuidador        | Como solicitante, quiero recibir una notificación clara cuando un cuidador me envíe un nuevo mensaje para poder responder rápidamente.                      |
| HU-015        | Ver opciones de pago y retiro                             | Como solicitante, quiero ver las opciones de pago disponibles. Como cuidador, quiero ver las opciones de retiro de fondos disponibles.                      |
| HU-016        | Realizar pago y recibir confirmación                      | Como solicitante, quiero realizar un pago de forma segura y recibir una confirmación exitosa.                                                              |
| HU-017        | Recibir pago por servicio completado                      | Como cuidador, quiero recibir el pago por los servicios que he completado de forma segura a través de la plataforma.                                       |
| HU-018        | Configurar método de retiro y solicitar retiro            | Como cuidador, quiero configurar mi método de retiro y solicitar la transferencia de mis fondos disponibles.                                               |
| HU-019        | Acceder a preguntas frecuentes                            | Como usuario (solicitante o cuidador), quiero acceder a una lista de preguntas frecuentes para encontrar respuestas rápidas a mis dudas más comunes.       |
| HU-020        | Buscar en la sección de ayuda                             | Como usuario (solicitante o cuidador), quiero buscar información específica dentro de la sección de ayuda utilizando palabras clave.                       |
| HU-021        | Contactar con el soporte a través de chat en vivo         | Como usuario (solicitante o cuidador), quiero contactar con el soporte a través de chat en vivo para recibir asistencia.                                   |
| HU-022        | Diseño responsive                                         | Como usuario quiero poder acceder a un landing page responsive desde un dispositivo de cualquier tamaño.                                                   |
| HU-023        | Registro desde Landing Page                               | Como usuario quiero acceder al formulario de inicio de sesión desde el landing page.                                                                       |
| HU-024        | Idiomas disponibles para la plataforma                    | Como usuario, quiero que la página esté disponible en varios idiomas (español e inglés) para navegar en mi idioma preferido.                               |
| HU-025        | Método POST para consultas de usuarios                    | Como administrador, quiero que cuando el usuario envíe el formulario de contacto, se realice un método POST a la API y yo pueda ver las consultas enviadas. |



---

## 3.3. Impact Mapping
En esta sección se describen y muestran los Impact Mappings, los cuales fueron desarrollados a partir de los User Personas. Estos mapas incluyen los objetivos de negocio de cada uno y permiten identificar las funcionalidades necesarias para generar los entregables definidos.

## Impact Mapping 1 – CareMe

![Impact Mapping de CareMe](https://i.imgur.com/lJjB3mV.png)

## Impact Mapping 2 – CareMe 

![Impact Mapping Versión 2 de CareMe](https://i.imgur.com/Gz7PsMN.png)

---

## 3.4. Product Backlog

A continuación, el backlog priorizado de funcionalidades agrupadas por épicas y con asignación de Story Points:

## Historias de Usuario Priorizadas – CareMe

| #  | User Story ID | Título                                           | Descripción                                                                                                                                                                  | Story Points |
|----|----------------|--------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------|
| 1  | HU01-EP01      | Buscar cuidadores ingresando dirección          | Como solicitante, deseo buscar cuidadores ingresando una dirección específica para encontrar opciones cercanas a mi domicilio.                                              | 3            |
| 2  | HU02-EP01      | Ajustar radio de búsqueda                       | Como solicitante, deseo poder ajustar el radio de búsqueda para ampliar o reducir el área de cobertura.                                                                     | 2            |
| 3  | HU03-EP01      | Mostrar estado de actividad del cuidador        | Como solicitante, deseo ver claramente si un cuidador está actualmente activo o no en la plataforma.                                                                        | 1            |
| 4  | HU04-EP01      | Buscar cuidadores usando mi ubicación actual    | Como solicitante, deseo buscar cuidadores utilizando la ubicación actual de mi dispositivo para encontrar opciones cercanas a donde me encuentro.                          | 3            |
| 5  | HU01-EP02      | Acceder a la página de registro de solicitante  | Como nuevo usuario, deseo acceder a una página específica para registrarme como solicitante.                                                                                | 1            |
| 6  | HU02-EP02      | Registrarse como solicitante proporcionando información básica | Como nuevo usuario, deseo registrarme como solicitante proporcionando mi nombre, correo electrónico y número de teléfono, y estableciendo una contraseña.          | 5            |
| 7  | HU03-EP02      | Ver mi perfil                                   | Como solicitante registrado, deseo poder acceder a la sección de mi perfil para revisar la información que he proporcionado.                                               | 2            |
| 8  | HU01-EP03      | Cancelar un servicio programado                 | Como solicitante, deseo poder cancelar un servicio de cuidado programado en caso de necesidad, siguiendo las políticas de cancelación.                                      | 3            |
| 9  | HU02-EP03      | Ver el historial de servicios completados       | Como solicitante, deseo poder ver un registro de los servicios de cuidado que ya se han completado.                                                                         | 2            |
| 10 | HU03-EP03      | Confirmar asistencia a un servicio programado   | Como cuidador, deseo poder confirmar mi asistencia a un servicio de cuidado programado antes de la fecha y hora de inicio.                                                  | 2            |
| 11 | HU04-EP03      | Marcar un servicio como completado              | Como cuidador, deseo poder marcar un servicio de cuidado como completado una vez que lo haya finalizado.                                                                   | 2            |
| 12 | HU01-EP04      | Iniciar conversación                            | Como solicitante o cuidador, deseo poder iniciar una conversación con un cuidador específico después de verlo en la lista de búsqueda o en su perfil.                     | 5            |
| 13 | HU02-EP04      | Recibir notificación de nuevo mensaje del cuidador | Como solicitante, deseo recibir una notificación clara cuando un cuidador me envíe un nuevo mensaje para poder responder rápidamente.                                | 3            |
| 14 | HU01-EP05      | Gestión de Pagos y Transacciones                | Como solicitante, quiero ver las opciones de pago disponibles antes de confirmar un servicio. <br><br>Como cuidador, quiero ver las opciones de retiro de fondos.           | 2            |
| 15 | HU02-EP05      | Realizar pago y recibir confirmación            | Como solicitante, quiero realizar un pago de forma segura y recibir una confirmación exitosa.                                                                               | 5            |
| 16 | HU03-EP05      | Recibir pago por servicio completado            | Como cuidador, quiero recibir el pago por los servicios que he completado de forma segura a través de la plataforma.                                                        | 3            |
| 17 | HU04-EP05      | Configurar método de retiro y solicitar retiro  | Como cuidador, quiero configurar mi método de retiro y solicitar la transferencia de mis fondos disponibles.                                                                | 5            |
| 18 | HU01-EP06      | Acceder a preguntas frecuentes                  | Como usuario (solicitante o cuidador), quiero acceder a una lista de preguntas frecuentes para encontrar respuestas rápidas sobre el uso de la plataforma.                  | 1            |
| 19 | HU02-EP06      | Buscar en la sección de ayuda                   | Como usuario (solicitante o cuidador), quiero poder buscar información específica dentro de la sección de ayuda utilizando palabras clave.                                 | 3            |
| 20 | HU03-EP06      | Contactar con el soporte a través de chat en vivo | Como usuario (solicitante o cuidador), quiero poder contactar con un agente de soporte a través de chat en vivo para obtener asistencia inmediata.                   | 8            |
| 21 | HU04-EP06      | Contactar con el soporte a través de correo electrónico | Como usuario (solicitante o cuidador), quiero poder contactar con el soporte a través de correo electrónico para dudas más complejas.                              | 2            |
| 22 | HU01-EP07      | Operaciones CRUD                                | Como usuario, quiero poder manejar la aplicación con las operaciones básicas de crear, leer, actualizar y borrar.                                                           | 8            |


---


