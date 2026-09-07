# Registro del experimento — SeniorLink

## 1. Punto de partida
- **Hipótesis priorizada:** Creemos que los adultos mayores jubilados completarán un formulario de perfil digital (habilidades e intereses) de forma autónoma. Lo sabremos si la tasa de finalización del formulario de registro supera el 45% sin abandono en los primeros pasos.
- **Pregunta de aprendizaje:** ¿Los adultos mayores jubilados son capaces de completar de forma autónoma un perfil digital con sus habilidades e intereses y mostrar intención real de postularse a una oportunidad sugerida?
- **Experimento mínimo:** Prototipo interactivo / Concierge de página única con formulario de perfilado guiado (4 preguntas) y catálogo con 5 oportunidades sugeridas con botón de postulación.
- **Métrica:** Tasa de finalización del formulario de perfil y tasa de clics en "Me interesa esta oportunidad".
- **Criterio de éxito:** Al menos el 45% de los convocados completa el perfil y al menos el 25% hace clic para sumarse a una actividad/trabajo.

## 2. Posición inicial en la curva de la verdad
- **Evidencia disponible:** Informes institucionales de la OMS/OPS sobre la pérdida de rol en el retiro y 3 entrevistas cualitativas de la Clase 2 que confirmaron la desestructuración de la tarde y el deseo de aportar conocimiento.
- **Incertidumbre pendiente:** Desconocíamos si los usuarios tolerarían un flujo de perfilado digital sin frustrarse y si existiría intención real de postularse a actividades simuladas.
- **Inversión autorizada:** Herramientas gratuitas no-code y prototipo web ligero en HTML/JS. Cero costo económico y menos de 2 horas de desarrollo.

## 3. Instrumento construido por la IA
- **Tipo de instrumento:** Micro Web App Prototipo interactivo (archivo `index.html` autoejecutable en navegador).
- **Enlace o archivo:** `index.html` (alojado localmente y distribuido como prototipo web interactivo).
- **Qué incluye:**
  - Pantalla 1: Formulario con tipografía grande y accesible (Nombre, edad, experiencia laboral previa, tipo de actividad buscada y disponibilidad horaria).
  - Pantalla 2: Catálogo con 3 categorías de oportunidades (Mentoría a jóvenes, Tarea administrativa flexible en Pyme y Taller comunitario) con botón "Me interesa".
  - Mensaje de confirmación y captura visual del interés.
- **Qué quedó fuera:** Base de datos relacional, login con contraseña, pasarela de cobros, mensajería interna y matching automatizado por IA (MVP completo descartado para no invertir de más).

## 4. Ejecución
- **Fecha y contexto:** Del 1 al 4 de septiembre de 2026. Prueba realizada enviando el enlace del prototipo por WhatsApp a jubilados del entorno extendido del equipo (familiares, conocidos de talleres y excolegas).
- **Participantes, escenarios, fuentes o datos:** 25 adultos mayores jubilados (rango de 60 a 73 años; 14 mujeres y 11 hombres; perfiles de educación secundaria/universitaria con autonomía digital básica).
- **Tarea realizada:** Abrir el enlace en el celular o PC, responder las preguntas del perfil y explorar las oportunidades para presionar "Me interesa" en caso de encontrar alguna afín.
- **Resultados obtenidos:**
  - De 25 personas que abrieron el prototipo, **14 completaron el formulario de perfilado** (56% de tasa de finalización).
  - De esas 14 personas, **8 hicieron clic en "Me interesa"** en al menos una oportunidad (32% del total de participantes; 57% de los que completaron el perfil).
  - Distribución de interés: 4 eligieron "Mentor de Emprendedores Jóvenes", 3 eligieron "Taller de Oficios y Experiencias" y 1 eligió "Asistencia Administrativa en Pyme".
- **Anomalías observadas:**
  - 4 participantes se trabaron en la pregunta de "área de experiencia" porque su trayectoria combinaba varios oficios y el menú desplegable solo permitía elegir una opción.
  - 3 participantes llamaron por teléfono o enviaron un mensaje de audio preguntando si al presionar "Me interesa" ya estaban asumiendo un compromiso legal o si les iban a cobrar algo.

## 5. Evidencia
- **A favor:**
  - El 56% completó el formulario de forma autónoma, superando el umbral de éxito del 45%.
  - El 32% realizó una postulación activa (superando el 25% fijado como criterio).
  - Las opciones de mentoría y transmisión comunitaria tuvieron 7 de los 8 clics, confirmando el deseo de roles con sentido social por sobre tareas administrativas rutinarias.
- **En contra:**
  - 11 de los 25 participantes abandonaron el prototipo al ver el formulario o no avanzaron tras la primera pantalla.
  - La necesidad de aclaración sobre gratuidad y compromiso muestra que el lenguaje de la interfaz todavía genera desconfianza.
- **Interpretación del equipo:** El concepto de "LinkedIn Senior" despierta tracción real cuando se orienta a proyectos de mentoría y aporte intergeneracional, pero la interfaz debe ser más flexible en la selección de habilidades y explicitar claramente la gratuidad y el carácter voluntario de la inscripción.
- **Limitaciones:** Los participantes eran contactos cercanos o referidos de las integrantes del equipo, lo que genera un sesgo de benevolencia inicial y mayor predisposición a probar la herramienta que un usuario desconocido.

## 6. Aprendizajes
- **Qué aprendimos:** Que los jubilados no buscan replicar su empleo formal anterior en formato part-time; lo que más valoran es ser consultados o escuchados en roles de guía (mentorías).
- **Qué continúa siendo un supuesto:** Todavía es un supuesto si organizaciones, Pymes o universidades reales estarían dispuestas a pagar o sostener operativamente esta plataforma (lado de la demanda y modelo de negocio).
- **Cambios realizados o propuestos:**
  - Cambiar el selector de experiencia por casillas de selección múltiple (checkboxes).
  - Agregar un texto visible arriba del formulario: *"Registro 100% gratuito. Vos decidís cuándo y cuánto participar"*.

## 7. Estado de la evidencia y próxima iteración
- **Respaldada, no respaldada o inconclusa:** **Respaldada.**
- **Comparación con el criterio:** La tasa de registro alcanzada (56%) superó el criterio de éxito ($\ge 45\%$) y la tasa de postulación (32%) superó el umbral requerido ($\ge 25\%$).
- **Decisión de iteración:** Avanzar hacia la siguiente incertidumbre (validar la demanda real de organizaciones y la experiencia de una sesión real de mentoría).
- **Justificación:** Habiendo reducido el riesgo de que los jubilados rechacen la tecnología para registrarse, el cuello de botella ahora pasa por saber si hay personas u organizaciones del otro lado interesadas en recibir su aporte.
- **Próxima incertidumbre por reducir:** ¿Existen jóvenes emprendedores, estudiantes u ONGs dispuestos a coordinar y asistir puntualmente a una sesión de asesoramiento con un mentor senior?

## 8. Nueva posición en la curva de la verdad
- **Evidencia incorporada:** Comportamiento real de 25 usuarios frente a un flujo digital interactivo, con métricas de conversión y patrones de preferencia temática registrados.
- **Inversión que se justifica ahora:** Diseñar un experimento de doble vía (lado demanda) o una prueba piloto de mentoría manual (Concierge) de 1 a 2 semanas coordinando 3 encuentros reales vía videollamada.
- **Qué todavía no se justifica construir:** Desarrollar una aplicación nativa para tiendas (App Store / Play Store), contratar servidores o programar un panel de administración complejo.
