## Predicción de enfermedades cardiovasculares

Librerías utilizadas: `Pandas`, `Numpy`, `Matplotlib`, `Seaborn` y `Scikit-Learn`

El presente proyecto intenta predecir si una persona padece o no de una enfermedad cardiovascular en base a características como la edad, la altura, el peso, si es fumadora o no, si hace ejercicio, su nivel de colesterol y otras variables descriptoras que se encuentran dentro del dataset original. A partir del procesamiento de los datos se crearon dos dataset nuevos; uno con los outliers y el otro sin ellos, con el fin de comparar si la precisión de los modelos se veía afectado por estos valores. Se utilizaron varios algoritmos de clasificación, en los cuales destaca el LightGBM por su rapidez y precisión.

Se pudo observar que todos los algoritmos tuvieron un desempeño parecido. En promedio, el accuracy obtenido fue de 73% tanto para los algoritmos que trabajaron con el dataset que contiene los outliers, como para los algoritmos que trabajaron con el dataset sin outliers.

Para correr el repositorio de forma local se debe crear un entorno virtual con el siguiente comando:

    Python3 -m venv nombre_entorno_virtual

Se debe activar el entorno virtual e instalar las librerías requeridas a través del archivo requirements.txt

    pip install -r requirements.txt
