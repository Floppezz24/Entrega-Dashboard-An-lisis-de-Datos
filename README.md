# Entrega-Dashboard-An-lisis-de-Datos

#Análisis del uso de asistentes de IA por estudiantes

#Descripción del proyecto
Este proyecto consiste en un análisis sencillo sobre cómo los estudiantes utilizan asistentes de Inteligencia Artificial. El objetivo es entender para qué tipo de tareas se usan, cuánto tiempo se dedica a cada sesión y si los estudiantes quedan satisfechos con la experiencia. Para ello, se ha trabajado con un conjunto de datos en formato CSV y se ha creado un dashboard en Google Sheets para visualizar los resultados.

#Estructura del proyecto
El repositorio está organizado de la siguiente manera:
├── ai_assistant_usage_student_life.csv   # Datos originales
├── README.md                             # Explicación del proyecto
└── Google Sheets (enlace)                # Limpieza, análisis y dashboard

#Instalación y requisitos
Para realizar este proyecto no ha sido necesario instalar ningún programa adicional.
Herramientas utilizadas:
* Google Sheets
* GitHub
El análisis se ha realizado directamente en Google Sheets a partir del archivo CSV.

#Limpieza y transformación de los datos
Antes de comenzar el análisis, se realizó una limpieza básica de los datos en Google Sheets:

* Se revisaron las columnas para asegurar que los datos fueran correctos.
* Se eliminaron filas vacías o incompletas.
* Se comprobó que los valores categóricos fueran coherentes.
* Se ajustó el formato del archivo CSV (cambio de puntos por comas) para una correcta visualización.
* Se verificó que los campos de fecha tuvieran formato correcto y se normalizaron los valores booleanos de UsedAgain para facilitar el análisis.

Los datos estaban bien estructurados, por lo que no fue necesario realizar transformaciones complejas.

#Análisis descriptivo de los datos
Los datos incluyen identificadores de sesión, nivel y disciplina del estudiante, fecha y duración de la sesión, tipo de tarea, nivel de asistencia de IA, resultado final de la tarea, si volverían a usar la IA y el nivel de satisfacción. El análisis se centró en aspectos básicos como:
* El número total de sesiones registradas. 
* La duración media de las sesiones.
* El nivel medio de satisfacción.
* Los resultados finales de las tareas.
* El uso de la IA según el tipo de tarea.
* El uso de la IA según el nivel del estudiante.
* Además del análisis por tipo de tarea y nivel del estudiante, se exploró la relación entre la duración de la sesión y la satisfacción recibida, así como la frecuencia de uso según disciplina académica.

#Dashboard
Se creó un dashboard en Google Sheets para mostrar los datos de forma visual y fácil de entender.
El dashboard incluye:
* Indicadores principales:
  * Total de sesiones.
  * Duración media de las sesiones.
  * 
* Gráficos:
  * Uso de la IA por tipo de tarea.
  * Distribución del nivel de los estudiantes.
  * Resultados finales de las sesiones.
  * Reutilización del asistente de IA.
    
* Filtros:
  * Tipo de tarea.
  * Nivel del estudiante.
  * Tipos de estudios.

Enlace al dashboard (modo lectura):
https://docs.google.com/spreadsheets/d/1Bu068iiDPgHgFCXeXJWRnUZ2Jruht-MByWCRsEcAdWk/edit?usp=sharing

#Resultados y conclusiones
A partir del análisis realizado, se observa que los estudiantes utilizan los asistentes de IA principalmente para tareas académicas. En general, el nivel de satisfacción es positivo y muchos usuarios indican que volverían a utilizar este tipo de herramientas, lo que demuestra que la IA puede ser útil como apoyo en los estudios.

#Próximos pasos

Como posibles mejoras del proyecto se podrían:

* Analizar más datos o un periodo de tiempo más largo.
* Comparar el uso de la IA entre diferentes disciplinas.
* Añadir más gráficos o métricas al dashboard.

# Autores y agradecimientos

Proyecto realizado por Ferran López Delgado con fines académicos.
