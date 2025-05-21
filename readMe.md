# Diálogo Socrático Asistido por IA

Esta es una aplicación web sencilla y muy útil que te permite entablar un diálogo socrático guiado por una Inteligencia Artificial. La IA asume el rol de Sócrates y te guía a través de las diferentes fases del método socrático, lo que la hace ideal para explorar ideas, creencias o conceptos de forma estructurada y profunda.

## ¿Qué es el Diálogo Socrático Asistido por IA?

La aplicación simula un diálogo con Sócrates, donde tú planteas una idea inicial y la IA te interpela con preguntas diseñadas para ayudarte a examinar, refutar y, finalmente, comprender mejor tus propias ideas. Está estructurada en seis pasos clave del método socrático[cite: 56]:

1.  **Planteamiento de una cuestión**: Tú expones una idea o creencia inicial, como "¿Qué es la justicia?" o "¿Qué es la virtud?"[cite: 56]. La IA simplemente acusa recibo de tu planteamiento en este paso[cite: 58, 59].
2.  **Ironía socrática**: La IA, asumiendo el papel de Sócrates, se declara ignorante sobre el tema y te pide que le enseñes o aclares el concepto[cite: 60, 62]. Esto busca disipar la arrogancia y abrir el diálogo al examen[cite: 61, 63].
3.  **El interrogatorio (Elenchus)**: Esta es la fase central. La IA te hará una serie de preguntas cortas y precisas sobre tu definición o afirmación inicial[cite: 65, 66, 70]. Busca definiciones claras y universales, no solo ejemplos, y utiliza analogías o contraejemplos para probar la consistencia de tus respuestas[cite: 67, 68, 71].
4.  **Descubrimiento de contradicciones e inconsistencias**: A través de las preguntas, la IA te guía para que reconozcas las fallas, contradicciones o limitaciones en tu propio entendimiento[cite: 73, 75]. Tus respuestas sucesivas a menudo entrarán en conflicto con tu tesis inicial o con otras creencias que sostienes[cite: 74, 76].
5.  **Aporía (desconcierto o impasse)**: Llegas a un estado de confusión o perplejidad al darte cuenta de que no sabes lo que creías saber[cite: 78, 79]. Este es un paso crucial, ya que el reconocimiento de la propia ignorancia es el comienzo de la sabiduría[cite: 79, 81]. La IA te invita a reflexionar sobre este desconcierto[cite: 81].
6.  **Hacia una nueva comprensión (el "parto" de las ideas)**: Aunque no siempre se llega a una definición final y satisfactoria, el objetivo es que, a través de este proceso de refutación y autoexamen, puedas "dar a luz" ideas más claras, mejor fundamentadas y más coherentes[cite: 83, 85]. La IA se ve a sí misma como una "partera" de ideas y te pregunta qué has aprendido o qué nuevas perspectivas has ganado[cite: 84, 86, 87].

## Cómo Usar la Aplicación

1.  **Configurar API Key**: Antes de iniciar el diálogo, debes configurar tu API Key. Haz clic en el botón "Configurar API Key" ubicado en la esquina superior derecha[cite: 7, 89].
    * Se abrirá una ventana modal[cite: 9, 10].
    * Selecciona tu **Proveedor API**: Puedes elegir entre "OpenAI" u "OpenRouter.ai"[cite: 49, 50].
    * Introduce tu **API Key** en el campo correspondiente[cite: 50].
    * Para **OpenAI**, puedes dejar el campo "Modelo" vacío para usar el modelo por defecto (`gpt-3.5-turbo`), o especificar otro[cite: 94, 95].
    * Para **OpenRouter.ai**, el modelo (`mistralai/mistral-7b-instruct`) se selecciona automáticamente y no se puede modificar en esta versión de la aplicación[cite: 98, 99].
    * Haz clic en "Guardar" para almacenar tu configuración[cite: 90, 195]. La aplicación guardará la API Key, el proveedor y el modelo en el almacenamiento local de tu navegador[cite: 195].

2.  **Iniciar Diálogo**: Una vez configurada tu API Key, haz clic en el botón "Iniciar Diálogo"[cite: 54, 184].
    * La aplicación te indicará el primer paso: "Planteamiento de una cuestión"[cite: 53, 56].
    * Se te pedirá que introduzcas la idea, creencia o concepto que deseas explorar en el área de texto[cite: 119, 184].

3.  **Interactuar con la IA**:
    * Escribe tu respuesta o tu planteamiento inicial en el cuadro de texto "Escribe tu respuesta aquí..."[cite: 54, 55, 120].
    * Presiona "Enviar" o la tecla "Enter" para enviar tu mensaje[cite: 171].
    * La IA (Sócrates) responderá de acuerdo con el paso actual del diálogo socrático[cite: 127, 128].
    * Observarás cómo el "Paso Actual" y su "Descripción" cambian a medida que avanzas en el diálogo[cite: 117, 118].
    * Un spinner y un mensaje de "Sócrates (IA) está pensando..." aparecerán mientras la IA genera su respuesta[cite: 125, 126].

4.  **Reiniciar Diálogo**: En cualquier momento, puedes hacer clic en "Reiniciar Diálogo" para borrar el historial de chat y comenzar un nuevo diálogo desde el principio[cite: 54, 185, 186].

## Consejos para una Mejor Experiencia

* **Sé conciso y claro**: Aunque la IA es tolerante, intenta ser lo más claro posible en tus respuestas para guiar mejor el diálogo.
* **Permite que la IA te guíe**: Confía en el proceso socrático. Las preguntas de la IA están diseñadas para hacerte reflexionar, incluso si al principio parecen sencillas o incómodas.
* **Explora diferentes temas**: Prueba a iniciar diálogos sobre diversas ideas para ver cómo la IA te ayuda a desentrañarlas.

¡Espero que disfrutes explorando tus ideas con tu propio Sócrates personal!