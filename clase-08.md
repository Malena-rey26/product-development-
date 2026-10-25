# Clase 8 — Pruebas, Medición y Mejoras del MVP (SeniorLink)

## 1. Contexto General
- **Equipo:** SeniorLink
- **Fecha:** Octubre 2026
- **Usuario:** Adultos mayores de 60 a 75 años recientemente jubilados.
- **Problema:** Desorientación, falta de rutina y pérdida de sentido de pertenencia tras dejar el mercado laboral formal.
- **Acceso al MVP:** Prototipo interactivo PWA en v0 (`https://v0.app/chat/s87Iw5oF7u2`).

---

## 2. Definición de la Tarea Principal y Métricas

### Tarea asignada al participante
> *"Imaginá que sos un jubilado que quiere compartir su experiencia o encontrar nuevas actividades. Explorá la plataforma, conectá con otros usuarios, administrá tus publicaciones y explorá la comunidad."*

- **Inicio:** Pantalla principal de la app (*Inicio*).
- **Criterio de finalización (Éxito):** Registro de usuario con País y Provincia, exploración de la pestaña *Perfiles*, envío/aceptación de solicitudes de amistad con revisión previa de perfil, y gestión de avisos en publicaciones propias.
- **Definición de ayuda:** Se considera ayuda si el participante requiere que el equipo le indique dónde presionar un botón.
- **Límite de intento:** Máximo 3 minutos por flujo.

### Definición de las 3 Métricas

| Métrica | Definición / Fórmula | Criterio de Éxito Exploratorio | Decisión que informa |
| :--- | :--- | :--- | :--- |
| **1. Éxito de la tarea** | Participantes que completan / Participantes que intentan | 4 de 4 participantes completan el recorrido | Confirma si la navegabilidad y estructura móvil resultan claras. |
| **2. Autonomía** | Participantes que completan sin ayuda / Participantes que intentan | 3 de 4 participantes completan sin ayuda | Muestra si las etiquetas, íconos y botones son autoexplicativos. |
| **3. Valor (Señal de Interés)** | Interacción con solicitudes de amistad, perfiles e intereses / Completados | 3 de 4 exploran la red social o ajustan intereses | Indica si las funciones de vinculación comunitaria generan engagement. |

---

## 3. Registro de Pruebas (Versión Inicial v1.0)

| ID | ¿Perteneció al segmento? | Versión | ¿Intentó? | ¿Completó? | ¿Sin ayuda? | Valor observado | Dificultad / Ayuda recibida |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **U1** | Sí (Jubilado) | Inicial v1.0 | Sí | Sí | Sí | Reaccionó con emojis en el canal | Flujo fluido y accesible. |
| **U2** | Compañero (Proxy) | Inicial v1.0 | Sí | Sí | No | Manifestó interés en ver la lista de amigos y perfiles | Pidió revisar el perfil de la persona antes de aceptar una solicitud. |
| **U3** | Compañero (Proxy) | Inicial v1.0 | Sí | Sí | Sí | Exploró la pestaña Perfil | Proceso intuitivo sin inconvenientes. |
| **U4** | Sí (68 años) | Inicial v1.0 | Sí | Sí | No | Consultó cómo editar sus temas de interés y seleccionar su provincia | Necesitaba mayor flexibilidad en la configuración de su perfil y ubicación. |

### Resultados Consolidados (Ronda 1)
- **Éxito de la tarea:** 4 / 4 (100%)
- **Autonomía:** 2 / 4 (50%)
- **Métrica de Valor:** 4 / 4 (100% interactuó con funciones sociales o de perfil)

---

## 4. Dificultad Priorizada e Iteración con IA

- **Hecho observado:** Los usuarios calificaron la interfaz como intuitiva, pero solicitaron poder ver el perfil de un usuario antes de aceptar su amistad, seleccionar su País y Provincia al registrarse, personalizar sus intereses y ver sus publicaciones y lista de amigos confirmados.
- **Posible causa:** Las versiones previas no contemplaban la vista previa de seguridad en solicitudes de amistad ni la categorización geográfica detallada.
- **Mejora elegida:** Rediseñar la sección *Perfil* (pestañas *Amigos*, *Publicaciones* e *Intereses*), incorporar selección desplegable de País y Provincia, permitir la revisión de perfil antes de responder a solicitudes y añadir opciones de *Bloquear* y *Reportar*.

### Pedido realizado a la IA (v0):
```text
Actualiza la app móvil de SeniorLink en v0 agregando:
1. Selección de País y Provincia/Estado mediante listas desplegables en el registro/edición de perfil.
2. Pestañas en Perfil: [Amigos] (renderizado dinámico), [Publicaciones] (vista completa) e [Intereses] (modal con selección múltiple).
3. Botón 'Ver perfil' previo en las solicitudes de amistad recibidas antes de Aceptar o Rechazar.
4. Botón 'Enviar aviso' integrado en cada tarjeta de actividad creada por el usuario.
5. Botones de seguridad 'Bloquear' y 'Reportar usuario' en perfiles de otros miembros.
