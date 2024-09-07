# <a name="_toc176478917"></a><a name="_hlk176118348"></a>**3. Capítulo III: Requirements Specification**
   ## <a name="_toc176478918"></a>**3.1. To-Be Scenario Mapping**
   ## <a name="_toc176169123"></a><a name="_toc176478919"></a>**3.2. User Stories**

|<p>**Epic / Story**</p><p>**ID**</p>|**Título**|**Descripción**|<p>**Criterios de**</p><p>**Aceptación**</p>|<p>**Relacionado**</p><p>**con (Epic ID)**</p>|
| :-: | :-: | :-: | :-: | :-: |
|**EP001**|Registro de Usuario|Como usuario nuevo, deseo registrarme en la plataforma para acceder a las funcionalidades del sistema|<p>**Escenario 1:**<br>**Dado** que soy un usuario nuevo,<br>**Cuando** ingreso mis datos correctos,<br>**Entonces** el sistema debería registrarme y enviarme un correo de confirmación.</p><p></p>|N/A|
|**EP002**|Gestión de Mascotas|Como usuario, deseo gestionar las mascotas bajo mi cuidado para mantener su información actualizada|**Escenario 1:**<br>**Dado** que soy un usuario registrado,<br>**Cuando** añado una nueva mascota,<br>**Entonces** debería poder guardar sus detalles y ver la información en mi perfil.|N/A|
|**EP003**|Notificaciones|Como usuario, deseo recibir notificaciones para estar al tanto de eventos importantes|<p>**Escenario 1:**<br>**Dado** que soy un usuario registrado,<br>**Cuando** se acerca una cita programada,<br>**Entonces** debería recibir una notificación de recordatorio.</p><p></p>|N/A|
|**EP004**|Gestión de Perfil|Como usuario, deseo gestionar mi perfil para mantener mi información personal actualizada|<p>**Escenario 1:**<br>**Dado** que soy un usuario registrado,<br>**Cuando** edito mis datos personales,<br>**Entonces** debería poder actualizar y guardar los cambios.</p><p></p>|N/A|
|**EP005**|Administración del Backend|Como desarrollador, deseo administrar el backend del sistema para garantizar el correcto funcionamiento|<p>**Escenario 1:**<br>**Dado** que soy un desarrollador,<br>**Cuando** realizo un cambio en la base de datos,<br>**Entonces** debería verificar que todas las dependencias se actualicen correctamente.</p><p></p>|N/A|
|**US001**|Inicio de Sesión|Como usuario registrado, deseo iniciar sesión para acceder a mi cuenta|<p>**Escenario 1:**<br>**Dado** que soy un usuario registrado,<br>**Cuando** ingreso mis credenciales correctas,<br>**Entonces** debería acceder a mi cuenta.</p><p>**Escenario 2:**<br>**Dado** que soy un usuario registrado,<br>**Cuando** ingreso credenciales incorrectas,<br>**Entonces** debería ver un mensaje de error indicando credenciales inválidas.</p>|EP001|
|**US002**|Recuperación de Contraseña|Como usuario, deseo recuperar mi contraseña para acceder a mi cuenta si la olvido|<p>**Escenario 1:**<br>**Dado** que olvidé mi contraseña,<br>**Cuando** ingreso mi correo registrado,<br>**Entonces** debería recibir un correo con un enlace para restablecerla.</p><p>**Escenario 2:**<br>**Dado** que ingresé un correo no registrado,<br>**Cuando** intento recuperar mi contraseña,<br>**Entonces** debería ver un mensaje de error indicando que el correo no existe.</p>|EP001|
|**US003**|Visualización de Historia Clínica|Como usuario, deseo visualizar la historia clínica de mis mascotas para revisar su historial médico|<p>**Escenario 1:**<br>**Dado** que soy un usuario registrado,<br>**Cuando** selecciono una mascota,<br>**Entonces** debería poder ver su historia clínica completa.</p><p>**Escenario 2:**<br>**Dado** que soy un usuario registrado,<br>**Cuando** no hay historial disponible,<br>**Entonces** debería ver un mensaje indicando que no hay información médica aún.</p>|EP002|
|**US004**|Agendamiento de Citas|Como usuario, deseo agendar citas veterinarias para organizar la atención de mis mascotas|<p>**Escenario 1:**<br>**Dado** que soy un usuario registrado,<br>**Cuando** elijo una fecha y hora,<br>**Entonces** debería poder confirmar y agendar la cita.</p><p>**Escenario 2:**<br>**Dado** que soy un usuario registrado,<br>**Cuando** intento agendar una cita en un horario no disponible,<br>**Entonces** debería ver un mensaje indicando la indisponibilidad.</p>|EP002|
|**US005**|Personalización de Notificaciones|Como usuario, deseo personalizar las notificaciones para recibir solo la información relevante|<p>**Escenario 1:**<br>**Dado** que soy un usuario registrado,<br>**Cuando** configuro las notificaciones,<br>**Entonces** debería poder elegir qué tipo de alertas deseo recibir.</p><p>**Escenario 2:**<br>**Dado** que soy un usuario registrado,<br>**Cuando** desactivo las notificaciones,<br>**Entonces** no debería recibir ninguna alerta hasta que las reactive.</p>|EP003|
|**US006**|Consulta de Servicios Veterinarios|Como usuario, deseo consultar los servicios veterinarios disponibles para seleccionar el adecuado|<p>**Escenario 1:**<br>**Dado** que soy un usuario registrado,<br>**Cuando** navego por los servicios,<br>**Entonces** debería poder ver una lista detallada de los mismos.</p><p>**Escenario 2:**<br>**Dado** que soy un usuario registrado,<br>**Cuando** selecciono un servicio específico,<br>**Entonces** debería ver los detalles y costos asociados.</p>|EP002|
|**US007**|Visualización de Historial de Citas|Como usuario, deseo visualizar mi historial de citas para hacer seguimiento de las visitas anteriores|**Escenario 1:**<br>**Dado** que soy un usuario registrado,<br>**Cuando** accedo a mi historial de citas,<br>**Entonces** debería poder ver todas las citas anteriores con sus detalles.||

||
| :- |

||||||
| :-: | :-: | :-: | :- | :-: |

|**Escenario 2:**<br>**Dado** que soy un usuario registrado,<br>**Cuando** no tengo citas anteriores,<br>**Entonces** debería ver un mensaje indicando que no hay citas en el historial.|
| :- |

|||||EP004|
| :-: | :-: | :-: | :- | :-: |
|**US008**|||||

||
| :-: |

||||||
| :-: | :-: | :-: | :- | :-: |

|Contacto con el Veterinario|
| :-: |

|||Como usuario, deseo contactar al veterinario para hacer preguntas o recibir asesoría|<p>**Escenario 1:**<br>**Dado** que soy un usuario registrado,<br>**Cuando** uso la función de contacto,<br>**Entonces** debería poder enviar un mensaje directamente al veterinario.</p><p>**Escenario 2:**<br>**Dado** que soy un usuario registrado,<br>**Cuando** no hay un veterinario disponible,<br>**Entonces** debería ver un mensaje indicando la falta de disponibilidad.</p>|EP002|
| :-: | :-: | :-: | :- | :-: |
|**US009**|Acceso al Foro de la Comunidad|Como usuario, deseo acceder a un foro comunitario para interactuar con otros dueños de mascotas|<p>**Escenario 1:**<br>**Dado** que soy un usuario registrado,<br>**Cuando** entro al foro,<br>**Entonces** debería poder leer y publicar mensajes en las discusiones.</p><p>**Escenario 2:**<br>**Dado** que soy un usuario registrado,<br>**Cuando** un mensaje viola las reglas del foro,<br>**Entonces** debería poder reportarlo a los moderadores.</p>|EP003|
|**US010**|Implementación de API RESTful|Como desarrollador, deseo implementar un API RESTful para la comunicación entre el frontend y backend|**Escenario 1:**<br>**Dado** que soy un desarrollador,<br>**Cuando** realizo un request de tipo GET,<br>**Entonces** debería recibir los datos solicitados en formato JSON.||

||
| :- |

||||||
| :-: | :-: | :-: | :- | :-: |

|**Escenario 2:**<br>**Dado** que soy un desarrollador,<br>**Cuando** realizo un request de tipo POST con datos válidos,<br>**Entonces** debería poder guardar la información en la base de datos.|
| :- |

|||||EP005|
| :-: | :-: | :-: | :- | :-: |
|**US011**|Monitorización de la Salud del Sistema|Como desarrollador, deseo monitorizar la salud del sistema para detectar problemas tempranos|<p>**Escenario 1:**<br>**Dado** que soy un desarrollador,<br>**Cuando** implemento un sistema de monitoreo,<br>**Entonces** debería recibir alertas automáticas en caso de fallas.</p><p>**Escenario 2:**<br>**Dado** que soy un desarrollador,<br>**Cuando** reviso los logs del sistema,<br>**Entonces** debería poder identificar y resolver problemas de rendimiento.</p>|EP005|
|**US012**|Landing Page|Como visitante, deseo ver la información en la Landing Page para conocer los servicios ofrecidos|<p>**Escenario 1:**<br>**Dado** que soy un visitante,<br>**Cuando** ingreso al sitio web,<br>**Entonces** debería ver una presentación clara de los servicios ofrecidos en la Landing Page.</p><p>**Escenario 2:**<br>**Dado** que soy un visitante,<br>**Cuando** hago clic en un servicio específico,<br>**Entonces** debería ser dirigido a una página con más detalles sobre ese servicio.</p>|N/A|
|**US013**|Contacto a través de la Landing Page|Como visitante, deseo contactar al equipo para obtener más información sobre los servicios|<p>**Escenario 1:**<br>**Dado** que soy un visitante,<br>**Cuando** lleno el formulario de contacto,<br>**Entonces** debería recibir una confirmación de que el mensaje fue enviado correctamente.</p><p>**Escenario 2:**<br>**Dado** que soy un visitante,<br>**Cuando** no completo todos los campos obligatorios del formulario,<br>**Entonces** debería ver un mensaje de error solicitando completar la información.</p>|US012|

## **<a name="_toc176478920"></a>3.3. Impact Mapping**
## <a name="_toc176169125"></a><a name="_toc176478921"></a>**3.4. Product Backlog**

|# Orden|User Story Id|Título|Descripción|<p>Story Points</p><p>(1 / 2 / 3 / 5</p><p>/ 8)</p>|
| :-: | :-: | :-: | :-: | :-: |
|1|US012|Landing Page|Como visitante, deseo ver la información en la Landing Page para conocer los servicios ofrecidos.|3|
|2|US013|Contacto a través de la Landing Page|Como visitante, deseo contactar al equipo para obtener más información sobre los servicios.|3|
|3|US001||||

||
| :-: |

|||<p></p><p>Inicio de Sesión</p>|Como usuario registrado, deseo iniciar sesión para acceder a mi cuenta.|2|
| :-: | :-: | :-: | :- | :-: |
|4|US003|Visualización de Historia Clínica|Como usuario, deseo visualizar la historia clínica de mis mascotas para revisar su historial médico.|5|
|5|US002|Recuperación de Contraseña|Como usuario, deseo recuperar mi contraseña para acceder a mi cuenta si la olvido.|2|
|6|US004|Agendamiento de Citas|Como usuario, deseo agendar citas veterinarias para organizar la atención de mis mascotas.|5|
|7|US006|Consulta de Servicios Veterinarios|Como usuario, deseo consultar los servicios veterinarios disponibles para seleccionar el adecuado.|3|
|8|US005|Personalización de Notificaciones|Como usuario, deseo personalizar las notificaciones para recibir solo la información relevante.|3|
|9|US007||||

||
| :-: |

|||<p></p><p>Visualización de Historial de Citas</p>|Como usuario, deseo visualizar mi historial de citas para hacer seguimiento de las visitas anteriores.|2|
| :-: | :-: | :-: | :- | :-: |
|10|US008|Contacto con el Veterinario|Como usuario, deseo contactar al veterinario para hacer preguntas o recibir asesoría.|3|
|11|US009|Acceso al Foro de la Comunidad|Como usuario, deseo acceder a un foro comunitario para interactuar con otros dueños de mascotas.|5|
|12|US010|Implementación de API RESTful|Como desarrollador, deseo implementar un API RESTful para la comunicación entre el frontend y backend.|8|
|13|US011||||

||
| :-: |

|||<p></p><p>Monitorización de la Salud del Sistema</p>|Como desarrollador, deseo monitorizar la salud del sistema para detectar problemas tempranos.|8|
| :-: | :-: | :-: | :- | :-: |
|14|US014|Gestión de Mascotas|||

||
| :-: |

||||Como usuario, deseo gestionar las mascotas bajo mi cuidado para mantener su información actualizada.|3|
| :-: | :-: | :-: | :- | :-: |
|15|US015|Registro de Usuario|Como usuario nuevo, deseo registrarme en la plataforma para acceder a las funcionalidades del sistema|5|
|16|US016|Administración del Backend|Como desarrollador, deseo administrar el backend del sistema para garantizar el correcto funcionamiento.|8|
