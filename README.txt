¿QUÉ HACE QUE UN TÍTULO EN NETFLIX EXPLOTE GLOBALMENTE?

DESCRIPCIÓN DEL PROYECTO
Este proyecto desarrolla una narrativa visual basada en datos para responder a la pregunta:
¿Qué características permiten anticipar si un título de Netflix tendrá alcance global?

A partir del Netflix Movies & TV Shows Dataset (aprox. 6.200 títulos), se construye un relato que transforma un análisis exploratorio y un modelo de Machine Learning en una historia clara, explicativa y accionable para tomadores de decisiones del negocio audiovisual.

El foco está en identificar señales estructurales, geográficas y textuales que se asocian con el potencial de internacionalización de un contenido antes de su lanzamiento.

DATASET UTILIZADO
Nombre: Netflix Movies & TV Shows Dataset
Fuente: Kaggle
Observaciones: ~6.234 títulos

Variables principales:
- País(es) de producción
- Tipo de contenido (Movie / TV Show)
- Año de lanzamiento
- Duración
- Género
- Descripción textual

FRAMEWORK NARRATIVO
Setup – Insight – Implicación

Setup:
Contextualización del problema de la internacionalización del contenido en Netflix.

Insight:
Identificación de patrones estructurales y textuales mediante análisis exploratorio de datos (EDA) y modelamiento.

Implicación:
Uso de estas señales para anticipar el potencial global y apoyar decisiones estratégicas.

MENSAJE CENTRAL
Los títulos con mayor potencial global comparten patrones textuales, geográficos y temáticos que pueden anticiparse con modelos de Machine Learning antes de su lanzamiento.

STORYTELLING Y VISUALIZACIONES

Exploración inicial (EDA):
- Scatterplot del número de países involucrados por título.
- Evolución temporal de las coproducciones multinacionales.
- Distribución de duración según tipo de contenido.

Visualizaciones explicativas:
- Comparación estructural entre formatos (películas y series).
- Análisis de estabilidad y variabilidad del contenido.
- Señales textuales asociadas al alcance global.

Visualización de síntesis:
- Distribución de scores de potencial global.
- Separación clara entre títulos con y sin potencial global.

MODELO ANALÍTICO
Se entrenó un modelo supervisado de clasificación utilizando variables estructurales y representaciones textuales (TF-IDF).
El modelo presenta una capacidad discriminativa consistente y permite interpretar términos asociados positiva y negativamente al alcance global.

RECOMENDACIÓN ACCIONABLE
Integrar un score de potencial global en las etapas tempranas de evaluación de contenido para priorizar decisiones de adquisición, promoción y posicionamiento internacional.
Este score debe complementar, y no reemplazar, el criterio editorial humano.

ESTRUCTURA DEL REPOSITORIO
/data      Dataset o scripts de descarga
/src       Código de análisis y modelamiento
/figures   Gráficos en alta resolución
/ppt       Presentación final

INSTRUCCIONES PARA REPRODUCIR
1. Clonar el repositorio.
2. Ejecutar los scripts o notebooks desde la carpeta /src.
3. Los gráficos se generan y guardan en /figures.
4. La presentación final se encuentra en /ppt.

USO DE INTELIGENCIA ARTIFICIAL
Se utilizó Inteligencia Artificial como apoyo para:
- Redacción iterativa del storytelling.
- Refinamiento de títulos narrativos.
- Revisión de coherencia narrativa y reducción de carga cognitiva.

PROMPTS UTILIZADOS

Prompt 1:
Actúa como experto en storytelling con datos y ayúdame a formular un mensaje central claro, evaluable y accionable.

Prompt 2:
Organiza los hallazgos del análisis usando el framework Setup – Insight – Implicación.

Prompt 3:
Justifica el uso de scatterplots para mostrar concentración de coproducciones internacionales.

Prompt 4:
Redacta una recomendación estratégica basada en evidencia cuantitativa para ejecutivos de una plataforma de streaming.

Prompt 5:
Revisa el storytelling para reducir carga cognitiva, eliminar redundancias y mejorar la fluidez narrativa.



BIBLIOGRAFÍA Y FUENTES
Netflix Movies & TV Shows Dataset – Kaggle
Material del curso Visualización de Datos y Storytelling

Nota:  Las justificaciones de los gráficos está en nota del presentador,  por favor considerar.
