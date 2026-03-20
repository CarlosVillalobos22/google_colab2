Explicación del Código: Sistema RAG con Interfaz Interactiva

Nombre: Carlos Eduardo Villalobos Sanchez
Carrera: TICS

Descripción

Este código implementa un sistema de RAG (Retrieval Augmented Generation) que permite realizar preguntas, buscar información dentro de un conjunto de documentos y generar respuestas utilizando inteligencia artificial mediante una interfaz gráfica interactiva.

<img width="339" height="239" alt="image" src="https://github.com/user-attachments/assets/36d58a07-2461-432c-80eb-cdb228efa3a9" />

¿Qué hace?
Instala todas las librerías necesarias para que el sistema funcione, incluyendo herramientas de inteligencia artificial, búsqueda vectorial y componentes de interfaz gráfica.

<img width="533" height="251" alt="image" src="https://github.com/user-attachments/assets/c97ff30d-0b02-48a1-b7f7-65855e9a5ede" />

¿Qué hace?
Importa todas las herramientas necesarias para el funcionamiento del sistema, incluyendo procesamiento de texto, modelos de lenguaje, búsqueda vectorial y elementos de interfaz.

<img width="435" height="112" alt="image" src="https://github.com/user-attachments/assets/1e11768d-cd55-47fb-8602-70feac5a69d9" />

¿Qué hace?
Verifica si el equipo cuenta con GPU disponible para acelerar la ejecución del modelo.

Documentos de ejemplo

<img width="682" height="259" alt="image" src="https://github.com/user-attachments/assets/61d211c8-f752-4a32-ab71-e8ad11beffda" />

¿Qué hace?
Define los textos que serán utilizados como base de conocimiento para responder preguntas.

División de documentos

<img width="577" height="130" alt="image" src="https://github.com/user-attachments/assets/6d9a04db-51b0-4c39-9453-0f59a39fc01f" />

¿Qué hace?
Divide los textos en fragmentos más pequeños para mejorar la precisión en la búsqueda de información relevante.

Embeddings y FAISS 

<img width="690" height="116" alt="image" src="https://github.com/user-attachments/assets/b635acfd-eae9-48b3-b859-d0ba5c063130" />

¿Qué hace?
Convierte los textos en vectores numéricos (embeddings) y los almacena en FAISS para realizar búsquedas por similitud semántica.

Modelo de lenguaje

<img width="450" height="212" alt="image" src="https://github.com/user-attachments/assets/87648852-2e6b-407e-a2c8-a3838bd7051a" />

¿Qué hace?
Carga el modelo de lenguaje y su tokenizador, los cuales se utilizan para generar respuestas basadas en el contexto recuperado.

Función para generar respuestas

<img width="575" height="311" alt="image" src="https://github.com/user-attachments/assets/95d972a0-5e09-4f30-a037-3d374dc300ba" />

¿Qué hace?
Genera una respuesta a partir de un texto de entrada utilizando el modelo de lenguaje.

Función RAG

<img width="608" height="428" alt="image" src="https://github.com/user-attachments/assets/dde5f28b-de55-41e6-9af3-81104ececd35" />
¿Qué hace?

Busca los documentos más relevantes según la pregunta del usuario.
Construye un prompt con instrucciones para guiar al modelo.

Genera la respuesta con el modelo y limpia texto innecesario.

Interfaz gráfica


<img width="571" height="417" alt="image" src="https://github.com/user-attachments/assets/00f7ad0e-8a3c-4e98-9ad4-44c0cbe6f5f6" />
<img width="483" height="152" alt="image" src="https://github.com/user-attachments/assets/b9411462-f3fa-4f94-9c97-7debb8a87cfd" />

¿Qué hace?
Crea los componentes de la interfaz: área de texto, botón de consulta y área de resultados.

Animación de carga

<img width="544" height="313" alt="image" src="https://github.com/user-attachments/assets/a5fc5b64-d5ab-4bdc-9aef-1af92233be07" />

¿Qué hace?
Muestra una animación mientras se genera la respuesta.

Evento del botón

<img width="471" height="446" alt="image" src="https://github.com/user-attachments/assets/5793d3a9-c921-4cfe-9b2e-c6345a6e77a5" />

¿Qué hace?
Obtiene la pregunta del usuario, ejecuta el sistema RAG y muestra los resultados.

Conexión y ejecución

<img width="311" height="90" alt="image" src="https://github.com/user-attachments/assets/920ad0c1-5924-4fe1-aa86-0a6bb3db16f2" />

¿Qué hace?
Conecta el botón con la función y muestra la interfaz completa.

Conclusión

Este código implementa un sistema completo de RAG que permite:

Buscar información en documentos.

Generar respuestas con inteligencia artificial.

Interactuar mediante una interfaz gráfica.

Es una base sólida para desarrollar aplicaciones más avanzadas de búsqueda inteligente y asistentes virtuales.

<img width="691" height="408" alt="image" src="https://github.com/user-attachments/assets/6b23f76f-de0e-4d40-b23b-05b4b3d1bdd8" />
<img width="1057" height="523" alt="image" src="https://github.com/user-attachments/assets/8f250f35-2bcf-4f3c-b4dd-7e7e8e060161" />




















