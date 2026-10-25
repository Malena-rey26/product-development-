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
  - El 32% hizo clic en "Me interesa" en al menos una oportunidad, superando el 25% fijado como criterio.
  - Las opciones de mentoría y transmisión comunitaria concentraron 7 de los 8 clics registrados.

- **En contra:**
  - 11 de los 25 participantes abandonaron el prototipo o no completaron el formulario.
  - Algunos participantes necesitaron aclaraciones sobre la gratuidad y el nivel de compromiso que implicaba presionar "Me interesa".

- **Interpretación del equipo:** Los resultados sugieren que las propuestas relacionadas con mentoría y transmisión de experiencia generaron mayor interés que la alternativa administrativa dentro de las opciones presentadas. También observamos que el formulario y algunos términos de la plataforma todavía pueden generar dificultades o dudas en ciertos usuarios.

- **Supuestos que continúan abiertos:** Todavía no sabemos si este comportamiento se mantendría con usuarios que no tengan relación con nosotras, las integrantes del equipo, si el interés expresado mediante un clic se convertiría en una participación real y si existirían organizaciones dispuestas a ofrecer oportunidades y sostener la plataforma.

- **Limitaciones:** Los participantes eran contactos cercanos a nosotras, lo que puede generar una mayor predisposición a probar la herramienta que la que tendría un usuario desconocido.

## 6. Aprendizajes
- **Qué aprendimos:** Que los jubilados no buscan replicar su empleo formal anterior en formato part-time; lo que más valoran es ser consultados o escuchados en roles de guía (mentorías).
- **Qué continúa siendo un supuesto:** Todavía es un supuesto si organizaciones, Pymes o universidades reales estarían dispuestas a pagar o sostener operativamente esta plataforma (lado de la demanda y modelo de negocio).
- **Cambios realizados o propuestos:**
  - Cambiar el selector de experiencia por casillas de selección múltiple (checkboxes).
  - Mostrar interés no implica ningún compromiso
    
  - ### Aprendizaje de las anomalías

**Anomalía 1 — Selección del área de experiencia**
- **Resultado inicial:** 4 participantes tuvieron dificultades para responder porque su experiencia abarcaba más de un área y el formulario permitía seleccionar solamente una.
- **Origen de la anomalía:** Instrumento. El formato de respuesta era demasiado limitado para representar distintas trayectorias laborales.
- **Decisión del equipo:** Mantener la pregunta, pero permitir seleccionar más de una opción.
- **Cambio propuesto:** Reemplazar el menú desplegable por casillas de selección múltiple.

**Anomalía 2 — Significado de "Me interesa"**
- **Resultado inicial:** 3 participantes consultaron si presionar "Me interesa" implicaba asumir un compromiso o realizar algún pago.
- **Origen de la anomalía:** Instrumento. El prototipo no explicaba con suficiente claridad qué implicaba realizar esa acción.
- **Decisión del equipo:** Aclarar que el registro es gratuito y que mostrar interés no obliga al usuario a participar.
- **Cambio propuesto:** Incorporar un mensaje visible que aclare la gratuidad y el carácter voluntario de la participación.

## 7. Estado de la evidencia y próxima iteración

- **Respaldada, no respaldada o inconclusa:** **Respaldada para esta prueba.**

- **Comparación con el criterio:** El 56% de los participantes completó el formulario, superando el criterio de éxito del 45%. Además, el 32% del total de participantes hizo clic en "Me interesa" en al menos una oportunidad, superando el criterio del 25%.

- **Decisión de iteración:** Avanzar hacia la siguiente incertidumbre: comprobar si existe interés real del otro lado de la plataforma y si el interés observado en oportunidades simuladas puede trasladarse a una experiencia real.

- **Justificación:** La prueba redujo la incertidumbre sobre la capacidad y disposición de los participantes para completar el perfil e interactuar con oportunidades dentro del prototipo. Sin embargo, todavía no sabemos si organizaciones reales estarían dispuestas a ofrecer oportunidades ni si el interés expresado mediante un clic se convertiría en participación efectiva.

- **Próxima incertidumbre por reducir:** ¿Existen organizaciones y posibles participantes interesados en concretar una experiencia real de mentoría o colaboración con un adulto mayor?

## 8. Nueva posición en la curva de la verdad

- **Evidencia incorporada:** Obtuvimos evidencia del comportamiento de 25 participantes frente a un prototipo digital interactivo: 56% completó el perfil y 32% hizo clic en al menos una oportunidad simulada. También identificamos dificultades concretas relacionadas con la selección del área de experiencia y con la interpretación del botón "Me interesa".

- **Incertidumbre que sigue abierta:** Todavía no sabemos si el interés observado se convertiría en participación efectiva frente a oportunidades reales ni si organizaciones reales estarían dispuestas a ofrecerlas.

- **Inversión que se justifica ahora:** Realizar una prueba pequeña del otro lado de la plataforma, contactando a algunas organizaciones o coordinando una experiencia real de mentoría de forma manual, sin desarrollar nuevas funcionalidades complejas.

- **Qué todavía no se justifica construir:** Una aplicación completa, una app para App Store o Play Store, servidores propios, un sistema de matching automatizado o un panel de administración complejo.
