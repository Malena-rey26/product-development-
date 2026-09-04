# Lean Product Canvas — SeniorLink (LinkedIn para Adultos Mayores)

> Este canvas contiene hipótesis. La evidencia surgirá de observar y experimentar.

## 1. Problema de negocio
Los adultos mayores recientemente jubilados (60 a 75 años) con autonomía e interés en mantenerse activos tienen dificultades para encontrar oportunidades laborales flexibles, proyectos de aporte comunitario o actividades recreativas estimulantes que se adapten a sus capacidades e intereses, lo que provoca desestructuración de su rutina diaria y una pérdida de talento y capital social para empresas y organizaciones.
- **Evidencia que lo respalda:** Informes de la OMS sobre la necesidad de participación social activa en el envejecimiento; entrevistas de la Clase 2 donde los usuarios manifestaron rechazo a ofertas infantilizantes y falta de canales directos para aplicar su experiencia.
- **Incertidumbre / Supuesto:** Todavía necesitamos comprobar si los adultos mayores completarán un perfil digital detallado por su cuenta y si existen empresas u organizaciones dispuestas a publicar oportunidades aptas para este segmento.

## 2. Resultados de negocio
- **Comportamiento / Registro:** Lograr que al menos el 40% de los usuarios mayores que ingresan completen su perfil de intereses, habilidades y disponibilidad horaria.
- **Conexión y Postulación:** Alcanzar un promedio de al menos 1 postulación o solicitud de unión a una actividad/trabajo flexible por usuario activo cada 15 días.
- **Validación de Demanda:** Conseguir al menos 15 ofertas activas (entre trabajos part-time, voluntariados calificados y actividades recreativas especializadas) publicadas por organizaciones o terceros en el primer mes.

## 3. Usuarios y clientes
| Rol | Definición | Estado de validación |
|---|---|---|
| **Usuario Principal** | Adultos mayores jubilados (60-75 años) con autonomía que buscan mantenerse productivos y socialmente activos. | Validado en entrevistas cualitativas (perfiles Jorge y Graciela). |
| **Oferentes de Oportunidades** | Pymes, consultoras, ONGs, clubes o centros culturales que buscan perfiles senior para tareas específicas o actividades guiadas. | Supuesto (pendiente de validación). |
| **Cliente / Pagador** | Empresas que pagan por publicar búsquedas de perfiles senior calificados o instituciones que patrocinan categorías temáticas. | Hipótesis de modelo de monetización. |
| **Influenciador** | Familiares directos (hijos/nietos) que recomiendan y asisten en la primera configuración de la cuenta. | Observado en entrevistas. |

## 4. Necesidades y resultados del usuario
- **Adulto Mayor Jubilado:** *Cuando* tengo tiempo libre y ganas de sentirme productivo, *quiero* encontrar opciones de trabajo adaptado o actividades estimulantes según lo que sé y me gusta hacer, *para* mantenerme activo, con propósito y sintiéndome valorado sin las exigencias de un empleo full-time tradicional.
- **Organización / Pyme:** *Cuando* necesito resolver tareas puntuales con personal confiable y experimentado, *quiero* acceder a perfiles senior disponibles por horas, *para* incorporar conocimiento probado de forma flexible y accesible.

## 5. Ideas de solución

### Alternativas evaluadas
1. **Opción A (Coordinación / Marketplace de Oportunidades):** *SeniorLink* — Red y plataforma digital donde el usuario carga sus habilidades e intereses mediante un flujo guiado y un recomendador le muestra ofertas de trabajo flexible y actividades afines. *(SELECCIONADA)*.
2. **Opción B (Información / Directorio simple):** *Bolsa de Empleo Tradicional Web* — Listado estático de avisos clasificados filtrables solo por ubicación. *(Descartada por no contemplar actividades recreativas ni personalización).*
3. **Opción C (Automatización / Chatbot):** *Asistente por WhatsApp* — Bot que envía semanalmente por mensaje 3 sugerencias. *(Descartada por limitar la autonomía visual y de exploración del usuario).*

### Ficha de la Solución Seleccionada: SeniorLink
- **Propuesta:** Plataforma digital accesible ("LinkedIn Senior") con perfiles simplificados por habilidades e intereses para conectar a adultos mayores con trabajos flexibles y actividades recreativas/comunitarias a su medida.
- **Valor para el usuario:** Autonomía, visibilidad de su experiencia, acceso a oportunidades adaptadas y eliminación de la fricción de los portales de empleo tradicionales.
- **Tecnología central:** Sistema de recomendación/matching por etiquetas (skills, tipo de actividad, carga horaria, modalidad presencial/remota) e interfaz adaptada (accesibilidad visual y navegación intuitiva).
- **Datos necesarios:** Habilidades previas, intereses recreativos, disponibilidad de días/horas, zona de residencia y requerimientos de las ofertas publicadas.
- **Riesgo principal:** Que el formulario de registro sea percibido como complejo o que haya escasez de oportunidades reales publicadas en la plataforma.
- **Prototipo inicial:** Directorio web interactivo en Softr / Glide conectado a una base en Airtable o Google Sheets.
- **Estado:** Idea no validada.

## 6. Hipótesis principales
- **Hipótesis de problema:** Creemos que los jubilados no encuentran hoy un canal centralizado y adaptado donde descubrir tareas y actividades acordes a su perfil. Lo sabremos si al menos 7 de cada 10 consultados manifiestan no conocer plataformas donde buscar actividades productivas o laborales para su edad.
- **Hipótesis de valor:** Creemos que al recomendar oportunidades personalizadas basadas en su perfil, el usuario se sentirá motivado a postularse o inscribirse. Lo sabremos si al menos el 30% de los usuarios que visualizan sugerencias personalizadas hace clic en "Quiero participar / Postularme".
- **Hipótesis de comportamiento (Adopción):** Creemos que los adultos mayores completarán un formulario de perfil digital (habilidades e intereses) de forma autónoma. Lo sabremos si la tasa de finalización del formulario de registro supera el 45% sin abandono en los primeros pasos.
- **Hipótesis de factibilidad:** Creemos que podemos montar una versión funcional de catálogo y registro con herramientas no-code (Glide/Softr + Airtable) sin requerir desarrollo a medida. Lo sabremos si lanzamos una webapp funcional en menos de 5 días con capacidad de filtrar y postularse.

## 7. Lo más importante por aprender
| Hipótesis | Incertidumbre (1-5) | Impacto (1-5) | Prioridad | Justificación |
|---|:---:|:---:|:---:|---|
| **Comportamiento (Registro/Perfilado)** | **5** | **5** | **ALTA (1ª)** | Si el jubilado se frustra al cargar sus datos o no entiende el formato de perfil digital, la plataforma se queda sin usuarios. |
| **Valor (Matching)** | 4 | 5 | Media (2ª) | Es indispensable que las opciones mostradas sean atractivas, pero depende de que primero se cree el perfil. |
| **Problema** | 2 | 4 | Baja (3ª) | La necesidad de mantenerse activo ya fue documentada por la OMS y las entrevistas previas. |
| **Factibilidad** | 2 | 3 | Baja (4ª) | Existen herramientas no-code para replicar un directorio tipo LinkedIn fácilmente. |

- **Pregunta central a responder:** *¿Los adultos mayores jubilados son capaces de completar de forma autónoma un perfil digital con sus habilidades e intereses y mostrar intención real de postularse a una oportunidad sugerida?*

## 8. Experimento mínimo (Prototipo No-Code / Concierge)
- **Hipótesis que prueba:** Hipótesis de comportamiento y adopción del perfil digital.
- **Objetivo:** Evaluar si los adultos mayores completan su perfil de habilidades/intereses y hacen clic en postularse a oportunidades simuladas.
- **Tipo de experimento:** Webapp prototipo interactivo en herramienta no-code (Glide o Softr) con datos precargados.
- **Herramientas:** Glide Apps / Softr + Google Forms / Airtable + WhatsApp para soporte/contacto.
- **Participantes:** 25 adultos mayores jubilados reclutados por el equipo.
- **Duración:** 5 días de prueba.
- **Tarea del participante:** Acceder desde el celular o computadora al link del prototipo, completar el cuestionario de perfil (3 minutos) y explorar 5 opciones de actividades/trabajos simulados acordes a su perfil, eligiendo al menos una para "postularse".
- **Datos necesarios:** Nombre, edad, rubro previo, intereses actuales (recreativos/laborales), horas disponibles por semana y botón presionado.
- **Métrica principal:** Tasa de finalización del formulario de perfil y tasa de clics en el botón de "Me interesa esta oportunidad".
- **Criterio de éxito:** Al menos el 45% de los convocados completa el perfil y al menos el 25% hace clic para sumarse a una actividad/trabajo.
- **Criterio de fracaso:** Menos del 15% completa el perfil o la mayoría manifiesta no entender cómo cargar sus datos o para qué sirve la plataforma.
- **Aprendizaje esperado:** Identificar qué preguntas del registro generan confusión, si prefieren oportunidades recreativas o remuneradas, y qué tipo de lenguaje visual resulta más accesible.
- **Limitaciones:** Las primeras oportunidades publicadas serán simuladas por el equipo para medir interés de demanda antes de salir a buscar clientes reales.

