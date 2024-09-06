# <a name="_toc176288609"></a>**3. Capítulo III: Requirements Specification**
   ## <a name="_toc176288610"></a>**3.1. To-Be Scenario Mapping**
***Segmento 1: Médicos Veterinarios***

![](./img/21.jpeg)

***Segmento 2: Dueños de Mascotas***

![](./img/22.jpeg)
## <a name="_toc176288611"></a>**3.2. User Stories**

|<p><a name="_hlk176169128"></a>**Epic / Story**</p><p>**ID**</p>|**Título**|**Descripción**|<p>**Criterios de**</p><p>**Aceptación**</p>|<p>**Relacionado**</p><p>**con (Epic ID)**</p>|
| :-: | :-: | :-: | :-: | :-: |
|**EP001**|Gestión de Usuarios|Como administrador, deseo gestionar los usuarios para asegurar que solo personas autorizadas tengan acceso al sistema.|<p>**Escenario 1:**</p><p>**Dado** que soy un administrador, </p><p>**cuando** reviso la lista de usuarios, </p><p>**entonces** debería poder ver, agregar, editar o eliminar usuarios según sea necesario.</p><p></p>|N/A|
|**EP002**|Gestión de Mascotas|Como usuario, deseo gestionar la información de mis mascotas para mantener sus datos actualizados.|<p>**Escenario 1:**</p><p>**Dado** que soy un usuario registrado, </p><p>**cuando** creo o edito el perfil de una mascota, </p><p>**entonces** debería poder almacenar y ver toda la información relevante sobre mis mascotas.</p>|N/A|
|**EP003**|Gestión de Citas Veterinarias|Como usuario, deseo gestionar las citas veterinarias de mis mascotas para asegurarme de que reciban atención médica a tiempo.|<p>**Escenario 1:**</p><p>**Dado** que soy un usuario registrado, </p><p>**cuando** agendo una cita veterinaria, </p><p>**entonces** debería poder ver la cita en mi calendario y recibir un recordatorio antes de la misma.</p>|N/A|
|**EP004**|Notificaciones y Recordatorios|Como usuario, deseo recibir notificaciones sobre eventos importantes relacionados con mis mascotas para estar siempre informado.|<p>**Escenario 1:**</p><p>**Dado** que soy un usuario registrado, </p><p>**cuando** se acerca una fecha importante (como una cita veterinaria o una vacunación), </p><p>**entonces** debería recibir una notificación o recordatorio con suficiente antelación.</p>|N/A|
|**EP005**|||||

||
| :-: |

||||||
| :-: | :-: | :- | :- | :-: |

|Foro Comunitario|
| :-: |

|||Como usuario, deseo participar en un foro comunitario para intercambiar experiencias y consejos con otros dueños de mascotas.|<p>**Escenario 1:**</p><p>**Dado** que soy un usuario registrado, </p><p>**cuando** participo en el foro comunitario, </p><p>**entonces** debería poder publicar, responder y reaccionar a las publicaciones dentro de un entorno seguro y moderado.</p>|N/A|
| :-: | :-: | :- | :- | :-: |
|**US001**|Registro de Usuario|Como nuevo usuario, deseo registrarme en la plataforma para acceder a sus funcionalidades.|**Escenario 1:** Dado que soy un usuario nuevo, cuando ingreso todos los datos requeridos correctamente, entonces debería poder registrarme y recibir un correo de confirmación. <br>**Escenario 2:** Dado que soy un usuario nuevo, cuando no completo un campo obligatorio, entonces debería ver un mensaje de error especificando los campos faltantes.|EP001|
|**US002**|Recuperación de Contraseña|Como usuario, deseo recuperar mi contraseña para acceder a mi cuenta si la olvido.|**Escenario 1:** Dado que olvidé mi contraseña, cuando ingreso mi correo registrado, entonces debería recibir un correo con un enlace para restablecerla. <br>**Escenario 2:** Dado que ingreso un correo no registrado, cuando intento recuperar mi contraseña, entonces debería ver un mensaje de error indicando que el correo no existe.|EP001|
|**US003**|Creación de Perfil de Mascota|Como usuario, deseo crear un perfil para cada una de mis mascotas para registrar su información.|**Escenario 1:** Dado que soy un usuario registrado, cuando ingreso los datos completos de una mascota, entonces debería poder crear un perfil para ella. <br>**Escenario 2:** Dado que soy un usuario registrado, cuando omito un campo obligatorio, entonces debería recibir un mensaje de error que indique el campo faltante.|EP002|
|**US004**|Edición de Perfil de Mascota|Como usuario, deseo editar el perfil de mis mascotas para mantener su información actualizada.|**Escenario 1:** Dado que soy un usuario registrado, cuando edito los datos de una mascota y guardo los cambios, entonces debería ver los cambios reflejados en el perfil de la mascota. <br>**Escenario 2:** Dado que soy un usuario registrado, cuando intento guardar un perfil sin un campo obligatorio, entonces debería recibir un mensaje de error.|EP002|
|**US005**|Agendamiento de Citas|Como usuario, deseo agendar citas para mis mascotas para planificar su atención veterinaria.|**Escenario 1:** Dado que soy un usuario registrado, cuando elijo una fecha y hora disponible, entonces debería poder confirmar y agendar la cita. <br>**Escenario 2:** Dado que soy un usuario registrado, cuando intento agendar una cita en un horario no disponible, entonces debería ver un mensaje indicando la indisponibilidad del horario.|EP003|
|**US006**|Cancelación de Citas|Como usuario, deseo cancelar una cita programada para reorganizar el calendario de atención de mis mascotas.|**Escenario 1:** Dado que soy un usuario registrado, cuando cancelo una cita con suficiente antelación, entonces debería recibir una confirmación de la cancelación. <br>**Escenario 2:** Dado que soy un usuario registrado, cuando intento cancelar una cita en el último momento, entonces debería recibir un mensaje indicando que la cancelación no es posible.|EP003|
|**US007**|Notificaciones de Citas|Como usuario, deseo recibir notificaciones de mis citas veterinarias para no olvidarlas.|**Escenario 1:** Dado que soy un usuario registrado, cuando se acerca la fecha de una cita, entonces debería recibir una notificación de recordatorio con los detalles de la cita. <br>**Escenario 2:** Dado que soy un usuario registrado, cuando una cita es cancelada, entonces debería recibir una notificación informándome de la cancelación.|EP004|
|**US008**|Notificaciones de Historial Médico|Como usuario, deseo recibir notificaciones cuando se actualiza la historia clínica de mi mascota para estar al tanto de su estado de salud.|**Escenario 1:** Dado que soy un usuario registrado, cuando el veterinario actualiza la historia clínica de mi mascota, entonces debería recibir una notificación sobre los cambios. <br>**Escenario 2:** Dado que soy un usuario registrado, cuando no hay cambios en la historia clínica, entonces no debería recibir notificaciones innecesarias.|EP004|
|**US009**|Publicación en el Foro|Como usuario, deseo publicar en el foro para compartir mis experiencias y obtener retroalimentación.|**Escenario 1:** Dado que soy un usuario registrado, cuando publico un mensaje en el foro, entonces debería poder verlo reflejado en la discusión correspondiente. <br>**Escenario 2:** Dado que soy un usuario registrado, cuando intento publicar un mensaje sin completar todos los campos necesarios, entonces debería recibir un mensaje de error.|EP005|
|**US010**|Moderación del Foro|Como moderador, deseo moderar el foro para asegurarme de que se mantenga un ambiente respetuoso y útil.|**Escenario 1:** Dado que soy un moderador, cuando recibo un reporte de un mensaje inapropiado, entonces debería poder revisarlo y tomar medidas como eliminar el mensaje o sancionar al usuario. <br>**Escenario 2:** Dado que soy un moderador, cuando un mensaje viola las reglas del foro, entonces debería poder eliminarlo y notificar al autor sobre la infracción.|EP005|

## ` `**<a name="_toc176288612"></a>3.3.Impact Mapping**
## <a name="_hlk176169129"></a> **<a name="_toc176288613"></a>3.4. Product Backlog**

|# Orden|User Story Id|Título|Descripción|<p>Story Points</p><p>(1 / 2 / 3 / 5</p><p>/ 8)</p>|
| :-: | :-: | :-: | :-: | :-: |
|1|US001|Registro de Usuario|Como nuevo usuario deseo registrarme en la plataforma para acceder a sus funcionalidades.|3|
|2|US002|Recuperación de Contraseña|Como usuario deseo recuperar mi contraseña para acceder a mi cuenta si la olvido.|2|
|3|US003|Creación de Perfil de Mascota|Como usuario deseo crear un perfil para cada una de mis mascotas.|3|
|4|US004|Edición de Perfil de Mascota|Como usuario deseo editar el perfil de mis mascotas para mantener su información actualizada.|2|
|5|US005|Agendamiento de Citas|Como usuario deseo agendar citas para mis mascotas para planificar su atención veterinaria.|3|
|6|US006||||

|Cancelación de Citas|
| :- |

||||||
| :-: | :-: | :- | :- | :-: |

||
| :- |

||||Como usuario deseo cancelar una cita programada para reorganizar el calendario de atención de mis mascotas.|2|
| :-: | :-: | :- | :- | :-: |
|7|US007|Notificaciones de Citas|Como usuario deseo recibir notificaciones de mis citas veterinarias para no olvidarlas.|3|
|8|US008|Notificaciones de Historial Médico|Como usuario deseo recibir notificaciones cuando se actualiza la historia clínica de mi mascota.|2|
|9|US009|Publicación en el Foro|Como usuario deseo publicar en el foro para compartir mis experiencias.|3|
|10|US010|Moderación del Foro|Como moderador deseo moderar el foro para asegurarme de que se mantenga un ambiente respetuoso.|5|
