---
dg-publish: true
date_modified: 2025-11-02T23:36:02-06:00
---

# NotebookLM

### Acceso oficial

#### Link

URL oficial: https://notebooklm.google.com

Disponibilidad:
* Web: Navegador en notebooklm.google.com
* Móvil: Apps oficiales en App Store (iOS 17+) y Play Store (Android 10+).
    En esta versión no se dispone de todas las funcionalidades.
* Requisitos: Cuenta de Google personal o Google Workspace

## Definición y propósito de NotebookLM

### Qué es NotebookLM

#### Definición

NotebookLM es un asistente de investigación y toma de notas, potenciado por inteligencia artificial y desarrollado por Google, diseñado para ayudar a los usuarios a analizar, sintetizar y generar ideas a partir de sus propias fuentes de información.

Su característica fundamental es el "source-grounding" (anclaje en fuentes): la herramienta crea un modelo de IA personalizado que se convierte en un experto exclusivamente en los documentos y materiales que el usuario proporciona. Estos pueden incluir archivos PDF, Google Docs, presentaciones, enlaces web, transcripciones de videos de YouTube, y más. Al no acceder a información externa de internet, NotebookLM garantiza que todas sus respuestas, resúmenes y análisis se basen únicamente en el contexto del material de origen.

Funciona como un asistente de investigación virtual capaz de:
* Resumir hechos y documentos extensos.
* Explicar ideas y conceptos complejos.
* Responder preguntas específicas utilizando la información cargada.
* Generar nuevas conexiones e ideas entre distintas fuentes.
* Crear contenido nuevo, como esquemas, borradores o resúmenes de audio estilo podcast.

En esencia, su propósito es transformar una colección de información compleja en una base de conocimiento clara, organizada y útil, permitiendo al usuario refinar y organizar sus ideas de manera más eficiente.

### Para qué sirve

> [!NOTE] Funciones principales:
> * Análisis profundo de fuentes: Procesa documentos, PDFs, sitios web, videos de YouTube, archivos de audio, Google Docs y Google Slides
> * Chat inteligente que responde preguntas con citaciones precisas y enlaces a fragmentos específicos
> * Creación de contenido diverso: Guías de estudio, informes, mapas mentales, FAQs, cronologías
> * Audio Overviews: Conversaciones tipo podcast entre hosts de IA sobre tu contenido
> * Video Overviews: Presentaciones narradas con diapositivas visuales

## Características técnicas relevantes

### Capacidades de procesamiento avanzadas

> [!NOTE] Note
> NotebookLM utiliza Gemini 1.5 Pro y Gemini 1.5 Flash con una ventana de contexto de 1 millón de tokens (expandiéndose a 2 millones), permitiendo procesar hasta 50 fuentes con 25 millones de palabras por notebook (de acuerdo a la versión utilizada). Su procesamiento multimodal nativo maneja texto, audio y video simultáneamente.

### Formatos de archivo soportados

> [!SUCCESS] Formatos Soportados
> - [ ] Google Workspace: Docs y Slides con importación directa desde Drive
> - [ ] Documentos: PDFs hasta 200MB, archivos de texto (.txt, Markdown)
> - [ ] Contenido web: URLs de sitios web y videos de YouTube con transcripciones
> - [ ] Audio: MP3 y WAV con transcripción automática
> - [ ] Texto directo: Fragmentos copiados y pegados

### Planes disponibles

> [!NOTE] Note
> **NotebookLM Gratuito:**
> * 100 notebooks con hasta 50 fuentes cada uno
> * Límites diarios: 50 consultas de chat, 3 Audio Overviews, 3 Video Overviews
> 
> **NotebookLM Plus (Premium):**
> * 5x más límites: 500 notebooks, 300 fuentes por notebook, 500 consultas diarias
> * Funciones avanzadas de personalización y analytics de uso
> * Protección de nivel empresarial y configuraciones avanzadas de chat

## Tutorial completo de funcionalidades

### Interfaz de usuario: diseño de tres paneles

La interfaz gráfica de usuario utiliza tres paneles especializados:

![[Pasted image 20251031223121.png]]

| Panel   | Función Principal                                                    |
| :------ | :------------------------------------------------------------------- |
| Fuentes | Subida y gestión de documentos, enlaces, PDFs, videos, etc.          |
| Chat    | Interacción con el modelo de IA, preguntas-respuestas, guardar notas |
| Studio  | Generar resúmenes, audios, mapas conceptuales; exportación           |



1.  **Panel de Fuentes (Izquierda)**
    * Administra toda la información central con botón "+ Agregar"
    * Lista de fuentes con toggles de activación/desactivación para seleccionar qué documentos usar
    * Función "Descubrir" para encontrar contenido automáticamente basado en un prompt.
2.  **Panel de Chat (Centro)**
    * Resumen automático generado al subir fuentes
    * Campo de entrada para preguntas específicas al modelo
    * Preguntas sugeridas por la IA para explorar el contenido
    * Respuestas con citaciones inline que enlazan a fragmentos específicos
    * Botones de acciones rápidas "Añadir nota", "Resumen de audio", "Mapa mental"
    * Botón "Guardar como nota" para preservar información importante del intercambio con el modelo
3.  **Panel de Studio (Derecha)**
    * Cuatro opciones principales: Audio Overviews, Video Overviews, Mind Maps, Reports
    * Múltiples outputs del mismo tipo por notebook
    * Personalización avanzada para cada tipo de contenido
    * Controles de reproducción integrados para audio y video

### Funcionalidades paso a paso



**A. Crear un cuaderno y cargar fuentes**
1.  Accede a https://notebooklm.google e inicia sesión con tu cuenta Google (Si no la tienes activa).
2.  Haz clic en "Crear cuaderno".
3.  Agrega tu primera fuente en el panel que se despliega.
4.  Agrega más fuentes haciendo clic en el botón "+ Agregar".
5.  Cada fuente se muestra como una tarjeta editable en el panel izquierdo (Fuentes).

[VIDEO: Tutorial de Carga de Archivos]

> [!TIP] ¡Manos a la obra!
> Prueba cargar archivos desde drive, audios u otros no mostrados en este tutorial.

**B. Editar fuentes**
1.  **Cambiar el nombre de una fuente**
    * Abre tu cuaderno y, en el panel Fuentes, pasa el cursor sobre la fuente.
    * Haz clic en el menú de tres puntos junto a la fuente y elige Renombrar (o "Rename").
    * Cambia el nombre de la fuente según tus preferencias.
        Puedes usar nomenclaturas para identificar mejor internamente cada fuente de tu notebook.
2.  **Quitar (eliminar) una fuente**
    * En el panel Fuentes, pasa el cursor sobre la fuente.
    * Abre el menú de tres puntos y selecciona Quitar/Eliminar fuente; confirma en el diálogo.
        (También puedes hacerlo desde ese mismo menú en implementaciones recientes).
3.  **Activar / desactivar una fuente (incluirla o excluirla de la respuesta)**
    * Marca o desmarca la casilla a la derecha del nombre de la fuente para incluirla o excluirla en el chat/sumario.
        (La casilla superior permite seleccionar/deseleccionar todas).

[VIDEO: Tutorial Edición de Fuentes]

**C. Cambiar idioma de salida**
Hace que todo lo que genere NotebookLM (guías de estudio, documentación, respuestas de chat y Resúmenes de Audio/Video) salga en el idioma que elijas.
1.  Abre NotebookLM en tu navegador (sesión iniciada con tu cuenta de Google).
2.  En la esquina superior derecha de la interfaz, haz clic en Configuración (ícono de engrane).
3.  En el panel de Configuración, selecciona la opción Idioma de salida (aparece como una fila/ajuste dentro del panel).
4.  En la lista desplegable, elige tu idioma preferido (por ejemplo, Español) y presiona "Guardar".
5.  La elección se aplicará al contenido que NotebookLM genere en adelante.

[VIDEO: Tutorial Cambiar Idioma]

**D. Consultar y conversar sobre tus fuentes**
1.  **Ingresar consulta**: En el panel Chat, haz preguntas o peticiones específicas sobre tus fuentes ("Hazme un resumen sobre...", "Explica el concepto...", "¿Cuáles son los puntos clave de las fuentes?").
    Si no tienes una pregunta en mente, puedes comenzar usando las preguntas sugeridas en la parte inferior del panel de chat.
2.  **Acceder a citas directas**: Las respuestas siempre incluyen citas directas y recuperables de tus documentos.
    Haciendo clic sobre la cita se puede acceder al texto exacto referenciado en la fuente, el cual se mostrará en el panel de fuentes.
3.  **Guardar nota**: Cuando el chat te da una respuesta útil, pulsa "Guardar como nota".
    Las notas se almacenan junto a su fuente citada. Puedes acceder a tus notas guardadas en la parte inferior del panel de studio.

[VIDEO: Tutorial Consultar y Conversar]

**E. Descubrir fuentes**
> [!NOTE] Note
> Te permite encontrar e importar, directamente desde la web, fuentes relevantes a tu cuaderno para empezar más rápido y reunir un conjunto completo de materiales.

1.  **Pulsar "Descubrir"**: En tu cuaderno, mira la barra lateral izquierda. En el panel "Fuentes" verás los botones "Añadir fuente" y, justo al lado, "Descubrir". Haz clic en este botón.
    Se abrirá una ventana emergente para comenzar la búsqueda.
2.  **Escribe una consulta sobre tu tema**: En la ventana emergente, utiliza el campo "Describe sobre qué quieres obtener información" para redactar tu consulta.
    Si prefieres explorar ideas nuevas, pulsa el botón "Tengo curiosidad" en esa misma ventana.
3.  **Revisar los resultados**: Después de enviar tu consulta, aparecerá una lista de resultados. Cada tarjeta muestra el título, una breve descripción de por qué la fuente es relevante y un enlace para abrir la página completa en una pestaña nueva.
4.  **Seleccionar resultados**: Elige una o varias fuentes de la lista a partir de las casillas de verificación al costado de cada fuente.
5.  **Importar fuentes**: Una vez seleccionadas las fuentes, impórtalas a tu cuaderno presionando el botón "Importar". Al finalizar, las nuevas fuentes aparecen en el panel "Fuentes" listas para usarlas con el chat, resúmenes de audio/vídeo o mapas conceptuales.

[VIDEO: Tutorial Descubrir Fuentes]

**F. Generar material de estudio**

**F.1. Generar resúmenes de audio (Podcast AI)**
1.  **Identifica la tarjeta de "Resumen de audio"**: Ve al panel "Studio" e identifica en la parte superior "Resumen de audio".
2.  **Personaliza antes de generar**: En la tarjeta Resumen de audio, dirígete a los tres puntos en la parte superior derecha, después presiona "Personalizar":
    * **Idioma y duración**: Puedes configurar el idioma de salida y la duración del podcast en las secciones correspondientes.
    * **Instrucciones/guion**: en el recuadro ¿En qué deberían enfocarse los hosts de IA? escribe indicaciones claras (temas a cubrir, nivel de detalle, público, tono) sobre cómo desearías que fuera tu resumen de audio.
3.  **Genera el resumen de audio**. En la parte inferior derecha del menú de personalización encontrarás el botón "Generar", presiónalo para crear un audio estilo podcast donde dos voces de IA discuten y resumen tus fuentes.
    > [!WARNING] ¡Advertencia!
    > La generación del resumen de audio tardará varios minutos
4.  **Ajusta la reproducción**: En el reproductor del resumen (dentro de la tarjeta de Studio), abre el menú Más ( ) y elige Cambiar velocidad de reproducción para oírlo más rápido o más lento.
5.  **Comparte o descarga**: Desde el reproductor usa Compartir para enviar un enlace (asegúrate de que el cuaderno esté compartido con la persona o "Cualquiera con el enlace") o Descargar para guardar el archivo de audio y enviarlo por otros medios.