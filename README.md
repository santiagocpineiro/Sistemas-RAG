# Sistemas-RAG

Este proyecto contiene dos notebooks que implementan un sistema de Recuperación Automática de Información (RAG). Los notebooks están diseñados para procesar diferentes tipos de datos y generar respuestas utilizando modelos preentrenados y herramientas como Gradio para la interfaz de usuario.

## Requisitos

Antes de ejecutar los notebooks, asegúrate de tener el entorno configurado correctamente. Este proyecto utiliza Conda y todas las dependencias están definidas en el archivo `environment.yml`.

### 1. Crear el entorno Conda desde el archivo `environment.yml`:

    conda env create -f environment.yml

### 2. Activar el entorno:
    conda activate rag

### 3. Instalar TinyLlama:

Para ejecutar el notebook english_rag.ipynb, necesitas tener un modelo TinyLlama instalado y corriendo localmente.

**Notebooks**
1. english_rag.ipynb

Este notebook obtiene información sobre microplásticos de un sitio web y utiliza un modelo TinyLlama para procesar las respuestas de manera más comprensible. Además, tiene una interfaz de usuario generada con Gradio para facilitar la interacción.

    Requisitos: TinyLlama debe estar corriendo.
    Funcionamiento: El notebook obtiene datos de microplásticos desde una página web y utiliza el modelo TinyLlama para generar respuestas entendibles.
    Interfaz: Gradio se utiliza para la interfaz de usuario, lo que permite realizar consultas de manera interactiva.

Pasos para ejecutar:

    Asegúrate de tener el modelo TinyLlama corriendo (instrucciones de instalación arriba).
    Ejecuta las celdas del notebook en el orden correspondiente.
    Interactúa con la interfaz Gradio para realizar consultas.

2. spanish_rag.ipynb

Este notebook procesa información de un archivo PDF llamado Cenicienta.pdf. No utiliza el modelo TinyLlama ni tiene una interfaz, pero permite obtener información relevante del PDF de manera automatizada.