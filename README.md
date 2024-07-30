# Técnicas de clasificación en minería de datos con Knime. Aplicación a datos reales.

TFM. Máster Universitario en Estadística Aplicada 
Universidad de Granada

**Realizado por**: Francisco Gil Rodríguez

**Tutora**: Prof. Dra. Rocío Raya Miranda

---

### Resumen

La Minería de Datos Educativa (Educational Data Mining, EDM) es un campo
de investigación interdisciplinario que se centra en el uso de técnicas de minería
de datos para analizar datos educativos con el objetivo de mejorar los procesos de
enseñanza y aprendizaje. La EDM combina métodos de estadística, aprendizaje
automático, inteligencia artificial y bases de datos para explorar y descubrir patrones
en datos relacionados con la educación. 

KNIME es una plataforma de código abierto orientada al análisis de datos
que permite, a través de una interfaz intuitiva y visual, crear análisis complejos y
flujos de trabajo mediante componentes especializados en diferentes áreas como la
minería de datos, el aprendizaje automático o la visualización de datos. 

El objetivo principal del estudio es desarrollar un flujo de trabajo que permita la 
detección temprana de estudiantes en riesgo de no aprobar sus cursos, 
aplicando algunos de los algoritmos de clasificación de KNIME sobre los datos de estudio
 OULAD. Para ello, se exploran en este trabajo diferentes técnicas de clasificación 
 aplicada a datos educativos, haciendo uso de la plataforma KNIME. 
 
Como base teórica previa a la realización del proyecto, se revisa la bibliografía más 
reciente en este campo, de donde se extraen los temas de estudio, los métodos y algoritmos 
de clasificación más estudiados. El abandono de los estudiantes es un tema frecuente y nos 
servirá de referencia para nuestro estudio. También presentamos las fases de un proceso de 
minería de datos aplicado a los datos educativos, pasos que seguiremos en este proyecto: 
selección de datos, preprocesamiento de datos, transformación de datos, 
minería de datos, evaluación de patrones y, por último, representación del conocimiento. 

Se introducen también algunas técnicas de clasificación, y se seleccionan un subconjunto de 
ellas de entre las más presentes en los estudios revisados. Concretamente se han 
seleccionando Random Forest, Regresión Logística, Redes neuronales y Gradient Boosted Trees.

Se realiza un estudio de la arquitectura de KNIME y se compara con WEKA, una herramienta 
similar pero más antigua y, por tanto, más presente en estudios similares. 

Una vez presentada la base teórica necesaria, se describe el conjunto de datos OULAD, analizando 
las tablas que lo componen y sus relaciones. El conjunto de datos OULAD fue desarrollado 
y compartido por The Open University (OU) en el Reino Unido. Su propósito es proporcionar 
un recurso anonimizado que permita el análisis de datos educativos, facilitando 
la investigación en el ámbito de la minería de datos educativa. OULAD contiene información 
sobre cursos, estudiantes y sus interacciones con el Entorno Virtual de Aprendizaje (EVA) 
para una selección de siete cursos representativos, denominados módulos, impartidos en
 la OU durante los años 2013 y 2014. Este conjunto de datos incluye variables 
 académicas y demográficas que son relevantes para el análisis del 
 rendimiento estudiantil.

El estudio tiene como objetivo implementar un flujo de trabajo que permita predecir la 
clasificación de los estudiantes en diferentes tramos temporales (25%, 50%, 75% y 100% de 
la realización del curso). Esta división por tramos no es tan común en las investigaciones previas 
analizadas, y requiere un importante trabajo de preprocesamiento previo de los datos, más allá
de usar directamente las variables disponibles en el conjunto de datos. Diviendo en tramos 
podemos también identificar, lo antes posible, a aquellos estudiantes que podrían estar en riesgo 
 de abandonar o no completar el curso.

Con estos estudiantes potencialmente en riesgo, se busca llevar a cabo acciones proactivas que 
ayuden a reducir el fracaso académico. Esto puede incluir intervenciones como el envío de 
correos electrónicos, la programación de tutorías individuales o la propuesta de materiales de
 apoyo, con el fin de ``recuperar'' a estos estudiantes o mejorar su desempeño. Se plantea la 
 posibilidad de volver a aplicar el modelo de predicción después de un tiempo para evaluar 
 si los estudiantes han salido de la zona de riesgo o si se requieren acciones adicionales, 
 de forma que se plantea un enfoque dinámico y adaptativo en la gestión del rendimiento de los
 estudiantes. 

Tras la descripción de los flujos de trabajo implementados, se comentan también los resultados, 
comparando los modelos empleados e identificando las variables con mayor peso en la predicción. 

Por último, se plantean algunas acciones que se podrían llevar a cabo durante el desarrollo 
de acciones formativas reales, haciendo hincapié en los mejores momentos para realizar y repetir 
el análisis (primer cuarto, mitad del curso y recta final); algunas dificultades que se pueden 
encontrar para implementar el estudio en la práctica; y qué acciones se pueden llevar a cabo en 
función del momento en que se realiza el análisis. 