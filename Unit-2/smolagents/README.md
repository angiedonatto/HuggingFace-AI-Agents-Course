# Unidad 2.1 — smolagents

## Cronograma académico

**5 de noviembre de 2026 (America/Bogota):** ejercicios de herramientas, recuperación, coordinación multiagente y visión.

## Recorrido práctico

| Notebook | Enfoque |
| --- | --- |
| [03 — Code Agents](03_Code_Agents.ipynb) | Acciones expresadas en Python y herramientas personalizadas. |
| [04 — Tool Calling Agents](04_Tool_Calling_Agents.ipynb) | Llamadas estructuradas a herramientas. |
| [05 — Tools](05_Tools.ipynb) | Creación de herramientas, exportación e integración con el Hub y Spaces. |
| [06 — Retrieval Agents](06_Retrieval_Agents.ipynb) | Búsqueda y recuperación de contexto. |
| [07 — Multi-Agent Systems](07_Multi_Agent_Systems.ipynb) | Delegación, datos con fuentes y visualización de ubicaciones. |

## Configuración

1. Abrir el notebook en Google Colab y ejecutar la celda inicial de dependencias.
2. Configurar `GROQ_API_KEY` en los secretos de Colab para la inferencia de Groq. Las celdas de Gemini utilizan `GEMINI_API_KEY` en Colab o `AGENTS_GEMINI_KEY` en variables de entorno.
3. Elegir modelos habilitados en la cuenta. `GROQ_MODEL_ID` y `GROQ_VISION_MODEL_ID` permiten personalizar los modelos de texto y visión.
4. Ejecutar las celdas en orden. Las herramientas locales pueden revisarse por separado de la inferencia del modelo.

Cada ejercicio dispone de un presupuesto propio de solicitudes, compartido con sus agentes delegados. `GROQ_MAX_REQUESTS` permite configurarlo. Los reintentos son acotados y respetan los límites indicados por el proveedor.

La generación de imágenes del Hub y la publicación de herramientas son opcionales y se habilitan mediante sus opciones de configuración. Requieren los permisos y cuotas correspondientes. El navegador utiliza Chromium de Playwright; `AGENTS_CHROMIUM_PATH` permite indicar una instalación existente.

## Elementos de aprendizaje

- Contratos de herramientas y comprobación de su uso en la traza del agente.
- Separación entre obtención de información, razonamiento y presentación.
- Conservación del contexto de llamadas y observaciones de herramientas.
- Coordinación entre un agente investigador y un agente gestor.
- Integración de imágenes y capturas mediante interfaces multimodales.

Las visualizaciones disponibles se conservan como ejemplos del recorrido. Los componentes interactivos se consultan en Colab o Jupyter.
