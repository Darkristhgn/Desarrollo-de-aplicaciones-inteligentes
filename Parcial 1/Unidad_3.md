### Actividad 3.1
**Generales**
	1. Problemas de búsqueda
		Encontrar una secuencia de acciones que lleve de un estado inicial a una meta.
	2. Espacios de estados
		Conjunto de todas las configuraciones posibles.
	3. Estado inicial
		Punto de partida de la búsqueda.
	4. Acciones
		Operaciones disponibles desde un estado.
	5. Método de transición
		Define a qué estado se llega al aplicar una acción.
	6. Prueba de meta
		Condición que indica que se llegó a una solución.
	7. Costo del camino
		Costo acumulado desde el estado inicial.
	8. Solución
		Costo acumulado desde el estado inicial.
	9. Frontera
		Nodos generados pero aún no expandidos.
	10. Nodo
		Estructura que guarda estado, padre, acción y costo.
	11. Agente de resolución de problemas
		Agente que formula una meta y busca la secuencia de acciones para lograrla.
*** 
**Búsquedas ciegas**
	1. Sistemas de búsqueda(Ciega)
		Exploran sin usar información del problema más allá de su definición.
	2. Búsqueda no informada(Ciega)
		A diferencia de la anterior esta si tiene una, guia de búsqueda
***
**Otros Conceptos**
	1. Búsqueda en amplitud
		explora nivel por nivel y encuentra el camino con menos pasos.
	2. Búsqueda en profundidad
		baja por una rama hasta el fondo antes de retroceder.
	3. Búsqueda uniforme
		expande siempre el nodo de menor costo acumulado (es Dijkstra).
	4. Cola
		estructura FIFO que usa BFS (con prioridad en UCS y A*).
	5. Pila
		estructura LIFO que usa DFS.
	6. Completitud
		Un algoritmo es completo si garantiza encontrar una solución cuando existe. BFS es completo si b es finito; DFS no lo es en espacios infinitos o con ciclos; UCS es completo si todos los costos son mayores que 0.
	7. Optimalidad
		Un algoritmo es óptimo si la solución que encuentra es la de menor costo. BFS es óptimo solo si todos los pasos cuestan lo mismo; UCS siempre es óptimo; DFS no lo es.
	8. Complejidad en tiempo
		BFS y DFS son $O(b^d)$ en el peor caso.
	9. Complejidad en espacio
		BFS guarda toda la frontera, $O(b^d)$
***
**Trabajo de clase**
**Búsqueda no informada**(ciega)
	No tiene ninguna pista sobre que tan cerca está la meta. Solo explora el espacio de estados con un orden fijo
	**Amplitud BFS**
		- Primero todos los estados a una distancia dada.
		- Encuentra la solución más corta(Con costos iguales)
		- Usa mucha memoria
		![[Pasted image 20261008171145.png]]
		Por lo que entiendo este recorre todos los caminos posibles mientras tengan costos iguales
	**Djikstra**
		![[Pasted image 20261008171322.png]]
		Por lo que veo en el ejemplo grafico djikstra lo hace de manera mas circular pero sigue siendo muy similar al BFS porque tambien se guia por costos iguales y recorre todos los caminos
	**Profundidad**
		Se va lo más lejos posible por un camino antes de retroceder
		Usa poca memoria
		No Garantiza la mejor solución y puede perderse en caminos infinitos