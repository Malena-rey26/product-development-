# Clase 7 — Construcción y Documentación del MVP (SeniorLink)

## 1. Definición del Producto
- **Nombre:** SeniorLink
- **Usuario objetivo:** Adultos mayores de 60 a 75 años recientemente jubilados.
- **Acción central:** Registro y perfilado del usuario senior, postulación a mentorías/actividades, vinculación directa entre pares mediante solicitudes de amistad y acceso a pasantías/empleos de medio tiempo.
- **Formato:** Prototipo interactivo PWA Móvil de 3 pantallas con navegación inferior (*Bottom Navigation Bar*) y selector de pestañas superiores (*Actividades* / *Perfiles de la comunidad*).

---

## 2. Alcance Técnico del MVP

### Lo que funciona (Funcionalidades reales en el prototipo):
- **Onboarding y Perfilado Completo:** Registro interactivo con datos personales, selector dinámico de **País** y **Provincia/Estado**, foto de perfil desde el dispositivo y gestión de intereses en lista desplegable.
- **Navegación e Interfaz Accesible:** 3 pantallas principales (*Inicio*, *Proponé...*, *Perfil*) con botones táctiles grandes, alto contraste y tipografía accesible (mínimo 18px).
- **Feed de Inicio y Publicación:** Carga de actividades con imagen ajustada en proporción y texto visible en tiempo real que impacta automáticamente en la pestaña *Publicaciones* del usuario.
- **Red Social y Comunidad:**
  - Pestaña de *Perfiles de la comunidad* y catálogo interactivo de miembros.
  - Centro de notificaciones/campana para solicitudes de amistad con vista previa del perfil antes de *Aceptar* o *Rechazar*.
  - Pestaña *Amigos* en el Perfil con tarjetas dinámicas de usuarios conectados.
  - Botones de seguridad (*Bloquear* y *Reportar usuario*) en perfiles ajenos.
- **Canal de Avisos e Interacción:** 
  - Integración del botón *Enviar aviso* dentro de la tarjeta de cada actividad creada.
  - Vista diferenciada: el creador administra y envía anuncios; los miembros unidos leen y reaccionan con emojis.
  - Restricción para que el creador administre su canal en lugar de autopostularse.

### Lo simulado / Fuera de alcance en esta versión:
- Conexión con base de datos remota en la nube (la información persiste localmente durante la sesión).
- Integración con la API biométrica de Mi Argentina / RENAPER (planteada como capa conceptual de seguridad Trust & Safety para la versión final).

---

## 3. Registro de Prueba y Feedback

- **Participantes:** 4 personas evaluadas (jubilados y proxies).
- **Resultado general:** Evaluaron la interfaz como sumamente intuitiva, clara y fácil de utilizar.
- **Ajustes implementados a partir de la retroalimentación:**
  - Se añadieron las pestañas de *Amigos*, *Publicaciones* e *Intereses* editables dentro del Perfil.
  - Se habilitó la vista previa del perfil antes de responder a una solicitud de amistad.
  - Se optimizó la visualización de fotos en el Feed y se centralizó el botón de *Enviar aviso* en las publicaciones creadas.

---

## 4. Enlace al Prototipo Interactivo
- **Ejecutable v0 (PWA):** `https://v0.app/chat/s87Iw5oF7u2`
