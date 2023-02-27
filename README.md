# Proyecto Final



1.1 Temática

FIFA 19 es un videojuego de simulación de fútbol desarrollado por EA Vancouver y EA Rumania, ayudando también en su desarrollo está también EA España y EA Holanda, como parte de la serie FIFA de Electronic Arts. Está disponible en las plataformas de Nintendo Switch, PlayStation 4 Microsoft Windows, Xbox One.
Como parte del estudio de analistas de datos de EA Argentina fuimos seleccionados a integrar el grupo de desarrollo del próximo FIFA. Contando con la base de datos de los jugadores disponibles, nos veremos abocados a la obtención, manipulación, procesamiento de datos con el propósito de detectar patrones y tendencias que optimicen la toma de decisiones estratégicas.

1.2 Presentación del equipo

Comisión 32675 Data Science
Juan Etchehun


1.3 Objetivos

El proyecto consiste en modelar las próximas actualizaciones de jugadores a lanzarse en el juego, de modo que, conforme a ciertos patrones de datos basado en sus atributos, predecir el posicionamiento ideal de un jugador dentro del campo.

2.1 Data Set

La información procesada se obtuvo de la base de datos publica de Kaggle
https://www.kaggle.com/datasets/karangadiya/fifa19

La misma cuenta con 1 archivo CSV file
El conjunto de datos de FIFA 18 que se ha utilizado para este análisis proporciona estadísticas de alrededor de 16000 jugadores en más de 70 atributos diferentes. Estos atributos son indicadores óptimos para determinar el desempeño de un jugador en una posición de juego en particular.
Para cada atributo, tenemos un número entero de 0 a 100 que mide qué tan bueno es un jugador en ese atributo. Ejemplos de atributos son: regate, agresividad, visión, marcaje y control del balón. Observe que parece inviable caracterizar con precisión a los jugadores en estos atributos automáticamente. Por lo tanto, todos ellos son recopilados y seleccionados por la empresa cuyo trabajo es acercar el juego a la realidad tanto como sea posible, preservando así la coherencia y la representatividad en todo el conjunto de datos.

2.2 Contenido

El conjunto de datos tiene las siguientes propiedades:

Todos los jugadores que aparecen en FIFA 18

más de 70 atributos

Datos de posición

Atributos basados en datos reales del último juego FIFA 18 de EA

Los atributos incluyen todas las estadísticas de estilo de jugador, como Dribbling, Aggression, GK Skills, etc.

Datos personales del jugador como nacionalidad, club, edad, sueldo, etc.

3.1 Análisis exploratorio de datos

Después de preparar el conjunto de datos para el análisis, se realizaron exploraciones a nivel macro, como el análisis de edad y rendimiento, edad y su potencial. A través del proceso se hicieron intentos de derivar correlaciones y tendencias interesantes mediante el uso de visualizaciones.


4.1 Prediccion de posicion

El objetivo final de nuestro enfoque es asignar una posición óptima a los jugadores según su conjunto de habilidades. En este caso, nuestro analisis final nos lleva a  predeterminar tres posiciones: atacante, defensores y arquero. Dado que hay muchas características que no son relevantes para deducir nuestros resultados, podemos descartarlas. Por lo tanto, la selección de características relevantes se realiza para mejorar la precisión del modelo al proporcionar datos de calidad al clasificador. Por ejemplo, atributos como la información personal son inútiles para entrenar al clasificador y, por lo tanto, pueden ignorarse para el análisis. El conjunto de datos tiene una columna donde se indica la posición preferida del jugador. A continuación, se asignan un total de 27 posiciones a las 3 clases predeterminadas.

Los modelos de aprendizaje automático utilizados en este enfoque son regresion logistica, random forest y redes neuronales. 


5.1 BIBLIOGRAFIA Y FUENTES

LIBRERIAS

numpy

pandas

plotly

seaborn

matplotlib

sklearn

Random

WEBSITES

https://kaggle.com/

https://www.ea.com/es-es/games/fifa/fifa-19

https://seaborn.pydata.org/

https://seaborn.pydata.org/examples/index.html

https://wiki.python.org/moin/PythonGraphLibraries

https://python-graph-gallery.com/

https://github.com/

https://plot.ly/python/

https://pandas.pydata.org/
