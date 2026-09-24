## Ejemplos de TEP

**Ejemplo 1: Filtro de correo spam**
- **Tarea (T):** Modificar comportamiento de NPC.
- **Experiencia (E):** Revisar el comportamiento de jugador (Agresivo, defensivo).
- **Medición (P):** Tiempo que tarda el jugador en pasar de fase.
**Ejemplo 2: Predicción de tráfico en una app de mapas**
- **Tarea (T):** Predecir cuánto tiempo tardará un vehículo en llegar de un punto A a un punto B en una ciudad.
- **Experiencia (E):** Datos históricos de viajes anteriores (rutas, horarios, velocidad promedio, día de la semana, condiciones climáticas, etc.).
- **Medición (P):** La diferencia entre el tiempo de llegada que predijo el sistema y el tiempo real que tardó el vehículo.

## Actividad 2.2

**Supervisado:** A este se le entregan datos los cuales ya están calificados como correctos y no correctos , mediante la visualización de estos el algoritmo empieza a iterar para minimizar el error 
**Sin supervisar**: A este modelo se da una instrucción y se le entregan los datos con características específicas sin resaltar cuales son los no correctos , una vez analizando los datos los clasifica en grupos y les agrega una etiqueta
**Por refuerzo:** Aquí se pone a un agente , no se la instrucción ni datos por si solo deberá saber cuál es su trabajo en caso de acercarse a la solución se le da una "recompensa" o un "castigo" de esta manera la máquina puede aprender que camino le da un refuerzo

## Actividad 2.3
Glosario
	**Machine Learning**
		Pandas: 
			Biblioteca de python escencial para ciencia de datos que funciona para trabajar con datos relacionales como Limpieza , tratamiento de datos , analisis exploratorio , soporte en machine learning etc.
		Matplotlib:
			Blioteca de python que sirve para representar graficamente
			Resultados , Patrones y Datos en si
		Scikit-learn:
			Biblioteca de python que optimiza el modelado estadistico y la ia , ademas Incluye módulos esenciales para clasificación, regresión, agrupación en clústeres y reducción de dimensionalidad
		Google Colab:
			Herramienta de google que se utiliza para escribir y correr codigo de python en linea
		Arbol de decision:
			es un algoritmo de aprendizaje supervisado no paramétrico, que se utiliza tanto para tareas de clasificación como de regresión. Tiene una estructura jerárquica, de árbol, que consta de un nodo raíz, ramas, nodos internos y nodos de hoja.
		Matriz de confusión:
			es una tabla que desglosa el número de instancias reales de una clase específica frente al número de instancias previstas para esa clase
		Sobreajuste:
			el sobreajuste ocurre cuando un modelo se ajusta demasiado o incluso exactamente a sus datos de entrenamiento, de modo que no puede hacer predicciones o conclusiones precisas a partir de ningún dato que no sea el de entrenamiento.
	**Generales**
		Falso positivo:
			Situacion en la que se asume que algo a tenido un resultado Erroneo cuando en realidad no
		Falso negativo:
			Situacion en la que se asume que algo a tenido un resultado Correcto cuando en realidad no