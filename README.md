# Hugging Face AI Agents Course

**Portafolio académico · Deep Learning — 2026-2**  
Universidad Externado de Colombia · Ciencia de Datos

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![smolagents](https://img.shields.io/badge/smolagents-FFD21E?style=flat-square&logoColor=black)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-7C3AED?style=flat-square)

| Información académica | Detalle |
| --- | --- |
| **Estudiante** | Angie Valentina Donato Pita |
| **Hugging Face** | [angiedonatto](https://huggingface.co/angiedonatto) |
| **Universidad** | Universidad Externado de Colombia |
| **Programa** | Ciencia de Datos |
| **Asignatura** | Deep Learning — 2026-2 |
| **Profesor** | Alber Montenegro |

## Presentación

Este repositorio reúne mi trabajo práctico en el [curso oficial de agentes de IA de Hugging Face](https://huggingface.co/learn/agents-course/en/unit0/introduction). A través de 16 notebooks exploro cómo un modelo de lenguaje puede interactuar con herramientas, recuperar información, coordinar tareas y trabajar con imágenes o interfaces web.

El recorrido conecta los fundamentos de los agentes con implementaciones en **smolagents, LlamaIndex y LangGraph**, y culmina en un ejercicio de **Agentic RAG**. Los notebooks reúnen implementaciones, salidas y observaciones para estudiar el comportamiento de cada enfoque.

### Objetivos de aprendizaje

- Comprender el ciclo de un agente: recibir una tarea, decidir una acción, usar una herramienta e interpretar su resultado.
- Construir herramientas con entradas y salidas definidas, y comparar acciones en Python con llamadas estructuradas.
- Integrar recuperación de información, memoria y fuentes externas para responder con contexto.
- Explorar coordinación multiagente, flujos con estado y capacidades de visión.
- Evaluar críticamente las respuestas, las trazas y las dependencias externas, distinguiendo resultados observados de validaciones pendientes.

## Estructura del repositorio

```text
HuggingFace-AI-Agents-Course/
├── README.md
├── Unit-1/                  # Fundamentos y primer agente · 01–02
├── Unit-2/
│   ├── smolagents/          # Unidad 2.1 · 03–09
│   │   └── README.md        # Cronograma y limitaciones de estos ejercicios
│   ├── llamaindex/          # Unidad 2.2 · 10–13
│   └── langgraph/           # Unidad 2.3 · 14–15
└── Unit-3/
    └── agentic-rag/         # Agentic RAG · 16
```

## Guía de notebooks

### Unidad 1 · Fundamentos

| Notebook | Objetivo |
| --- | --- |
| [01 · Dummy Agent Library — Groq](Unit-1/01_dummy_agent_library_GROQ_Colab.ipynb) | Explorar un agente básico y el intercambio entre instrucciones, acciones y observaciones con Groq. |
| [02 · First Agent — smolagents](Unit-1/02_First_Agent_smolagents.ipynb) | Configurar un primer agente con smolagents y conectarlo con herramientas. |

### Unidad 2.1 · smolagents

| Notebook | Objetivo |
| --- | --- |
| [03 · Code Agents](Unit-2/smolagents/03_Code_Agents.ipynb) | Construir agentes que expresan sus acciones mediante código Python y herramientas personalizadas. |
| [04 · Tool Calling Agents](Unit-2/smolagents/04_Tool_Calling_Agents.ipynb) | Comparar llamadas estructuradas a herramientas con acciones expresadas como código. |
| [05 · Tools](Unit-2/smolagents/05_Tools.ipynb) | Definir herramientas con decoradores y clases, y explorar herramientas del Hub y de Spaces. |
| [06 · Retrieval Agents](Unit-2/smolagents/06_Retrieval_Agents.ipynb) | Integrar búsqueda y una base de conocimiento como herramientas de recuperación. |
| [07 · Multi-Agent Systems](Unit-2/smolagents/07_Multi_Agent_Systems.ipynb) | Distribuir tareas entre agentes y organizar información recuperada en tablas y mapas. |
| [08 · Vision Agents](Unit-2/smolagents/08_Vision_Agents.ipynb) | Incorporar imágenes al razonamiento del agente y explorar inferencia visual, incluida la continuación con Gemini. |
| [09 · Vision Web Browser](Unit-2/smolagents/09_Vision_Web_Browser.ipynb) | Explorar navegación asistida por capturas de pantalla y herramientas de interacción web. |

### Unidad 2.2 · LlamaIndex

| Notebook | Objetivo |
| --- | --- |
| [10 · LlamaIndex Components](Unit-2/llamaindex/10_LlamaIndex_Components.ipynb) | Preparar documentos, embeddings e índices para consultas con recuperación de contexto. |
| [11 · LlamaIndex Tools](Unit-2/llamaindex/11_LlamaIndex_Tools.ipynb) | Crear herramientas de funciones y consultas, y explorar ToolSpecs. |
| [12 · LlamaIndex Agents](Unit-2/llamaindex/12_LlamaIndex_Agents.ipynb) | Combinar herramientas, memoria y recuperación en agentes y sistemas multiagente. |
| [13 · LlamaIndex Workflows](Unit-2/llamaindex/13_LlamaIndex_Workflows.ipynb) | Diseñar flujos por eventos con pasos, estado, bucles y bifurcaciones. |

### Unidad 2.3 · LangGraph

| Notebook | Objetivo |
| --- | --- |
| [14 · LangGraph Agent](Unit-2/langgraph/14_LangGraph_Agent.ipynb) | Definir un agente como grafo con estado, nodos, herramientas y transiciones. |
| [15 · LangGraph Mail Sorting](Unit-2/langgraph/15_LangGraph_Mail_Sorting.ipynb) | Modelar la clasificación de correos de ejemplo y la generación de borradores mediante rutas condicionales. |

### Unidad 3 · Agentic RAG

| Notebook | Objetivo |
| --- | --- |
| [16 · Agentic RAG](Unit-3/agentic-rag/16_Agentic_RAG.ipynb) | Integrar recuperación, búsqueda y herramientas en el ejercicio de la gala de Alfred. |

## Tecnologías y entorno de trabajo

| Tecnología | Uso en el recorrido |
| --- | --- |
| **Python y Google Colab** | Desarrollo de notebooks, experimentación y conservación de resultados. |
| **Hugging Face** | Material del curso, Hub, modelos, herramientas y ejemplos con Spaces. |
| **Groq y Gemini** | Inferencia de modelos; Gemini también aparece en las continuaciones de visión. |
| **smolagents** | Agentes con acciones en código, llamadas a herramientas y coordinación de tareas. |
| **LlamaIndex** | Componentes de recuperación, herramientas, agentes y workflows. |
| **LangGraph** | Orquestación de agentes mediante grafos y estado compartido. |

Para explorar un ejercicio, abrir su notebook en GitHub o Google Colab y revisar sus dependencias y configuración. Las credenciales que requieran los proveedores deben configurarse mediante secretos del entorno, sin incluir sus valores en el código ni en las salidas compartidas.

## Reflexiones sobre el aprendizaje

**Del modelo al sistema.** Mi principal aprendizaje ha sido entender que un agente requiere más que una buena respuesta del modelo: necesita herramientas bien definidas, contexto suficiente y una forma de comprobar lo que ocurrió. Comparar las tres bibliotecas me permitió estudiar distintas maneras de organizar esas responsabilidades.

**Recuperar también exige evaluar.** Los ejercicios de RAG, búsqueda y mapas muestran la importancia de revisar las fuentes y la correspondencia entre lo recuperado y la respuesta. Una traza de herramientas o una salida visual ayuda a inspeccionar el proceso, pero no garantiza por sí sola que cada dato sea correcto.

**Diseño y validación.** El recorrido me permitió trabajar la compatibilidad entre modelos y herramientas, la gestión de presupuestos de solicitudes y la comprobación de componentes. Las trazas, las fuentes y las pruebas locales ayudan a revisar el proceso de cada agente.

### Requisitos de ejecución

- Abrir los notebooks en Google Colab o en un entorno Python con las dependencias indicadas en sus primeras celdas.
- Configurar las claves de Groq y Gemini mediante secretos del entorno; seleccionar modelos habilitados para la cuenta.
- Disponer de conexión a Internet para búsqueda, imágenes y servicios del Hub. Las integraciones opcionales se controlan desde sus propias opciones de configuración.
- Utilizar Colab o Jupyter para las visualizaciones interactivas; GitHub ofrece una vista estática de los archivos.

El [README de smolagents](Unit-2/smolagents/README.md) incluye una guía de configuración de sus ejercicios.

## Certificación

**Certificación obtenida: Fundamentals of Agents.**

Esta certificación corresponde a los fundamentos de agentes. La evaluación final del curso continúa en proceso; sigo revisando los errores y trabajando para obtenerla.

---

Material de referencia: [Hugging Face Agents Course](https://huggingface.co/learn/agents-course/en/unit0/introduction). Este repositorio presenta mi trabajo académico y las adaptaciones de los ejercicios del curso.
