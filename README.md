Asistente de Entranamiento Fisico🏋️‍♂️

Este repositorio contiene una Prueba de Concepto (POC) de un asistente personal de entrenamiento físico basado en Inteligencia Artificial. El proyecto utiliza modelos de lenguaje de última generación (LLMs) y técnicas de Fast Prompting para ofrecer rutinas personalizadas y guías visuales de ejercicios de manera eficiente y rentable.

📌 El Problema

Mantener una rutina de ejercicio efectiva es difícil debido a la falta de personalización, el alto costo de los entrenadores personales y el riesgo de lesiones por mala técnica. Las aplicaciones actuales suelen ser genéricas o requieren múltiples interacciones costosas con la nube.

💡 La Solución

Un asistente inteligente que, mediante una única consulta optimizada, genera un plan de entrenamiento semanal completo. Este enfoque minimiza el uso de tokens y llamadas a la API, garantizando la viabilidad económica del proyecto a escala.

Características Principales:

Personalización Extrema: Basada en edad, nivel, objetivos y equipo disponible.

Generación Multimodal: Crea tanto el plan de texto como las imágenes explicativas en una sola llamada.

Optimización de Costos: Uso de técnicas de One-Shot Fast Prompting.

🛠️ Tecnologías Utilizadas

Lenguaje: Python 3.x

IA: Google Gemini API (Modelo gemini-2.5-flash-image-preview)

Entorno: Google Colab / Jupyter Notebooks

Librerías: google-generativeai, Pillow, IPython

🧠 Estrategia de Fast Prompting

Para asegurar la rentabilidad, implementamos:

Persona Pattern: Definimos un rol experto para la IA desde el inicio.

One-Shot Tasking: Agrupamos la recolección de datos y la generación de contenido (texto e imagen) en un solo bloque.

Output Structuring: Forzamos respuestas en Markdown para facilitar la integración en interfaces de usuario.

📊 Resultados Esperados

Al ingresar los datos del usuario, el sistema devuelve:

Un mensaje motivacional.

Rutina detallada por días con series y repeticiones.

Imágenes generadas por IA que muestran la ejecución correcta de los ejercicios.

📝 Conclusiones

Esta POC demuestra que es posible democratizar el acceso al entrenamiento de alta calidad utilizando IA. La optimización mediante Fast Prompting resuelve el cuello de botella de los costos operativos, haciendo que el proyecto sea escalable y rentable desde el primer día.
